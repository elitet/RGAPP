<template lang="pug">
.page
  .navbar.color-theme-black
    .navbar-inner.sliding
      .left
        a.link.back(href='#')
          i.icon.icon-back
          span.ios-only Back
      .title.M300 LINE UP
  .page-content
    // Content block
    .block
      a.color-white.margin-top.popup-open(href='#', data-popup='.popup-pregador')
        img.mt2(src='http://comu.com.br/app/rgconf/assets/img/musica.jpg' width='100%', alt='')
      br
      br
      a.color-white.margin-top(href='#')
        img.mt2(src='http://comu.com.br/app/rgconf/assets/img/mountains.jpg' width='100%', alt='')
      br
      br
      a.color-white.margin-top(href='#')
        img.mt2(src='http://comu.com.br/app/rgconf/assets/img/musica.jpg' width='100%', alt='')
      br
      br
  // PREGADOR
  .popup.popup-pregador.theme-dark
    .navbar.color-theme-black
      .navbar-inner
        .left
        .title.sliding.F18.M900 [NOME DO PRELETOR/BANDA]
        .right
          a.link.icon-only.popup-close(href='#')
            i.icon.f7-icons.ios-only close
            i.icon.material-icons.md-only close
    .page.theme-dark
      .block.RBLHT.F17
        p PREGADOR
        p
          | Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem.
  // PREGADOR

</template>
<script>
export default {};
</script>
