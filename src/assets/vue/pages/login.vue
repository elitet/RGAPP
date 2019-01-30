<template lang="pug">
.page
  .page-content
    form
      .block
        .row.justify-content-center
          .col-45.text-align-center.margin-top.padding-top
            img(src='http://comu.com.br/app/rgconf/assets/img/logo-rgconf.svg' width='100%')
        .list
          ul
            li.item-content.item-input.item-input-with-value
              .item-inner
                .item-title.item-label.M500 CPF
                .item-input-wrap
                  input#demo-username-2.input-with-value(type='tel', placeholder='')
                  span.input-clear-button
        .block
          button.button.button-raised.Cor1.button-big.button-fill.F17.M900 ENTRAR
          br
          button.button.button-raised.Cor2.button-big.button-fill.F17.M900 PRIMEIRO ACESSO
          br
          .block-footer.M500.text-align-center.color-white
            a.color-white(href='#') Esqueci a senha

</template>
<script>
export default {};
</script>
