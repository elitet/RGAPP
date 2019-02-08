<template lang="pug">
f7-page
  f7-navbar.color-black
    .title
      img.mt2(src='http://comu.com.br/app/rgconf/assets/img/logo.svg' width='45%', alt='')
  
  f7-block

    //-ul(v-if="categories && categories.length")
      //-li(v-for="category of categories")
        //-p {{category.Titulo}}

    f7-link.color-white.margin-top(v-bind:href="'/lineup/'+category.ID", v-if="categories && categories.length", v-for="category of categories")
      img.mt2(v-bind:src="category.Imagem" width='100%', alt='')
    br
    br

</template>
<script>
import axios from 'axios';
export default {
  data() {
    return {
      categories: [],
      errors: []
    }
  },

  // Fetches posts when the component is created.
  created() {
    axios.get('http://comu.com.br/app/rgconf/?acao=categorias')
    .then(response => {
      // JSON responses are automatically parsed.

      console.log(response.data);

      this.categories = response.data
    })
    .catch(e => {
      this.errors.push(e)
    })
  }
};
</script>
