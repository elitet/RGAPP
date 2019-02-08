<template lang="pug">
f7-page
  f7-navbar.color-black
    .left
      a.link.back(href="/")
        i.icon.icon-back
    .title.M300 LINE UP
    
  f7-block
    f7-link.color-white.popup-open(href='#', data-popup='.popup-pregador')
      img.mt2(src='http://comu.com.br/app/rgconf/assets/img/musica.jpg' width='100%', alt='')
    br
    br

  f7-popup.popup-pregador.theme-dark
    f7-navbar.color-theme-black(inner=true)
        f7-nav-left
        f7-nav-title.F18.M900 [NOME DO PRELETOR/BANDA]
        f7-nav-right
          f7-link.link.icon-only.popup-close(href='#')
            i.icon.material-icons close
    f7-page.theme-dark
      f7-block.RBLHT.F17
        p PREGADOR
        p
          | Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem.

</template>
<script>
export default {
  created(){
    let teste = this.$f7.views.main.router;
    console.log(JSON.stringify(teste));
    console.log(this.$f7.views.main.router.currentRoute);
    //-this.$f7.views.main.router.currentRoute.params
    //-this.$f7.dialog.alert(this.$f7.mainView);
  }
};
</script>
