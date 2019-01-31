<template lang="pug">
f7-page
  f7-navbar.color-black
    .left
      a.link.back(href="/")
        i.icon.icon-back
    .title.M900 NOTIFICAÇÕES

  f7-block
    f7-list(media-list=true, chevron-center=true)
      f7-link.item-link.item-content.popup-open(href='#', data-popup='.popup-notificacao')
        .item-inner
          .item-title-row
            .item-title.RBTREG Está chegando!
            .item-after 17:14
          .item-text.RBLHT.F17
            | Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis tellus ut turpis condimentum, ut dignissim lacus tincidunt. Cras dolor metus, ultrices condimentum sodales sit amet, pharetra sodales eros. Phasellus vel felis tellus. Mauris rutrum ligula nec dapibus feugiat. In vel dui laoreet, commodo augue id, pulvinar lacus.

  f7-popup.popup-notificacao.theme-dark
    f7-navbar.color-theme-black(inner=true)
        f7-nav-left
        f7-nav-title.F18.M900 Está chegando!
        f7-nav-right
          f7-link.link.icon-only.popup-close(href='#')
            i.icon.material-icons close
    f7-page.theme-dark
      f7-block.margin-top.RBLHT.F17
        p
          | Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

</template>
<script>
export default {};
</script>
