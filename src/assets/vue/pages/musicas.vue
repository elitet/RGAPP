<template lang="pug">
.page
  .navbar.color-theme-black
    .navbar-inner.sliding
      .left
        a.link.back(href='#')
          i.icon.icon-back
          span.ios-only Back
      .title.M300 MÚSICAS
  .page-content
    // Content block
    .block
      a.color-white.margin-top.popup-open(href='#', data-popup='.popup-musicas')
        img.mt2(src='http://comu.com.br/app/rgconf/assets/img/musica.jpg' width='100%', alt='')
      br
      br
      a.color-white.margin-top.popup-open(href='#', data-popup='.popup-musicas')
        img.mt2(src='http://comu.com.br/app/rgconf/assets/img/mountains.jpg' width='100%', alt='')
      br
      br
      a.color-white.margin-top.popup-open(href='#', data-popup='.popup-musicas')
        img.mt2(src='http://comu.com.br/app/rgconf/assets/img/musica.jpg' width='100%', alt='')
      br
      br
  // MÚSICAS
  .popup.popup-musicas.theme-dark
    .navbar.color-theme-black
      .navbar-inner
        .left
        .title.sliding.M900 Volto os meus olhos
        .right
          a.link.icon-only.popup-close(href='#')
            i.icon.f7-icons.ios-only close
            i.icon.material-icons.md-only close
    .page.theme-dark
      .block.RBLHT.F17
        br
        strong Dunamis Movement 
        p
          | Teu abraço em meio 
          br
          |             À noite me alcançou
          br
          |             Sem restrições
          br
          |             Se entregou por mim
          br
        p
        |             Quando eu te vejo
        br
        |             Não há mais o que dizer
        br
        |             Pois não há outro que me conhece igual a ti, Deus
        br
        p
        |             Volto os meus olhos
        br
        |             Para tua presença
        br
        |             Deixo tua glória ganhar forma em mim, em mim
        br
        p
        |             Bem melhor que a vida
        br
        |             É o teu amor
        br
        |             Jesus, seja o centro em mim
        br
        p
        |             E quando eu te vejo
        br
        |             Não há como duvidar que és bom
        br
        |             Quando clamamos teu nome tu vens
        br
        p
        |             Volto os meus olhos
        br
        |             Para tua presença
        br
        |             Deixo tua glória ganhar forma em mim
        br
        p
        |             Volto os meus olhos (pra ti Jesus)
        br
        |             Para tua presença
        br
        |             Deixo tua glória ganhar forma em mim
        br
        p
        |             Nossos olhos estão fixos em ti
        br
        |             Ganhar forma em nós
        br
        p
        |             Vem derramar tua glória
        br
        |             Queremos ver tua face, queremos ver tua face
        br
        |             Vem derramar tua glória
        br
        |             Queremos mais de ti, queremos mais de ti
        br
        p
  // MÚSICAS

</template>
<script>
export default {};
</script>
