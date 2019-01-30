<template lang="pug">
.page
  .navbar.color-theme-black
    .navbar-inner.sliding
      .left
        a.link.back(href='#')
          i.icon.icon-back
          span.ios-only
      .title.M900 MEU PERFIL
  .page-content
    .list.links-list.M500
      ul
        li
          a.panel-close Isabela Maria
        li
          a.panel-close email@teste.com
    .block
      .content-block.text-align-center.bg-color-white
        h2.green.M300.padding-top [INSCRIÇÃO #586746N]
        img(src='http://comu.com.br/app/rgconf/assets/img/qrcode.png' width='90%', alt='')
  // NOTIFICAÇÃO
  .popup.popup-notificacao.theme-dark
    .float-right.margin-top.margin-right.margin-bottom
      a.link.icon-only.popup-close(href='#')
        i.icon.f7-icons.color-white.ios-only close
        i.icon.material-icons.color-white.md-only close
    .page.theme-dark
      br
      br
      .block.margin-top.RBLHT.F17
        p
          | Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
  // NOTIFICAÇÃO

</template>
<script>
export default {};
</script>
