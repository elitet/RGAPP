<template lang="pug">
f7-page
  f7-navbar.color-black
    .left
      a.link.back(link="/")
        i.icon.icon-back
    .title.M300 HORÁRIOS

  f7-card-content.RBLHT.text-align-center(padding=true) Sujeito a alteração.
  f7-card
    f7-card-header.M900 SEXTA-FEIRA
    f7-card-content(padding=true)
      f7-row
        f7-col.mt2.M900(width="20") 19H
        f7-col.mt2.RBLHT(width="80") Início da recepção
      f7-row
        f7-col.mt2.M900(width="20") 20H
        f7-col.mt2.RBLHT(width="80") Abertura
      f7-row
        f7-col.mt2.M900(width="20")
        f7-col.mt2.RBLHT(width="80") Sessão 1
</template>
<script>
export default {};
</script>
