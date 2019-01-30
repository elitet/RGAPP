<template lang="pug">
.page
  .navbar.color-theme-black
    .navbar-inner.sliding
      .left
        a.link.back(href='#')
          i.icon.icon-back
          span.ios-only
      .title.M900 NOTIFICAÇÕES
  .page-content
    // Content block
    .block
      .list.media-list.chevron-center
        ul
          li
            a.item-link.item-content.popup-open(href='#', data-popup='.popup-notificacao')
              .item-inner
                .item-title-row
                  .item-title.RBTREG Está chegando!
                  .item-after 17:14
                .item-text.RBLHT.F17
                  | Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis tellus ut turpis condimentum, ut dignissim lacus tincidunt. Cras dolor metus, ultrices condimentum sodales sit amet, pharetra sodales eros. Phasellus vel felis tellus. Mauris rutrum ligula nec dapibus feugiat. In vel dui laoreet, commodo augue id, pulvinar lacus.
          li
            a.item-link.item-content.popup-open(href='#', data-popup='.popup-notificacao')
              .item-inner
                .item-title-row
                  .item-title.RBTREG Novo App!
                  .item-after 17:14
                .item-text.RBLHT.F17
                  | Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis tellus ut turpis condimentum, ut dignissim lacus tincidunt. Cras dolor metus, ultrices condimentum sodales sit amet, pharetra sodales eros. Phasellus vel felis tellus. Mauris rutrum ligula nec dapibus feugiat. In vel dui laoreet, commodo augue id, pulvinar lacus.
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
