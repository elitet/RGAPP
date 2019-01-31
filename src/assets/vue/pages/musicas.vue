<template lang="pug">
f7-page
  f7-navbar.color-black
    .left
      f7-link.link.back(href="/")
        i.icon.icon-back
    .title.M300 MÚSICAS
      
  f7-block
    f7-link.color-white.popup-open(href='#', data-popup='.popup-musicas')
      img.mt2(src='http://comu.com.br/app/rgconf/assets/img/musica.jpg' width='100%', alt='')
    br
    br

  f7-popup.popup-musicas.theme-dark
    f7-navbar.color-theme-black(inner=true)
        f7-nav-left
        f7-nav-title.M900 Volto os meus olhos
        f7-nav-right
          f7-link.link.icon-only.popup-close(href='#')
            i.icon.material-icons close
    f7-page.theme-dark
      f7-block.RBLHT.F17
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

</template>
<script>
export default {};
</script>
