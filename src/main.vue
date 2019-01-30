<template lang="pug">
// App
f7-app.theme-dark(:params='f7params')
    f7-statusbar
    f7-view.ios-edges(url='/', :main='true')
</template>
<script>
// Import Routes...
import routes from "./routes.js";

let theme = "md";
if (document.location.search.indexOf("theme=") >= 0) {
  theme = document.location.search.split("theme=")[1].split("&")[0];
}

export default {
  data() {
    return {
      f7params: {
        name: "RG|CONF",
        theme,
        routes,
        id: "io.framework7.testapp"
      }
    };
  }
};
</script>

<style>
.float-left {
  float: left;
}
.float-right {
  float: right;
}
.mt2 {
  margin-top: 2px;
}
.mt5 {
  margin-top: 5px;
}
.Htbs {
  min-height: 172px;
  line-height: 132px;
}
.green {
  color: #63d08c;
}

.F40 {
  font-size: 40px;
}
.F15 {
  font-size: 15px;
}
.F17 {
  font-size: 17px;
}
.F18 {
  font-size: 18px;
}
.M500 {
  font-family: "museo_sans500";
}
.M900 {
  font-family: "museo_sans900" !important;
}
.M300 {
  font-family: "museo_sans300" !important;
}
.M300i {
  font-family: "museo_sans300" !important;
  font-style: italic;
}
.M100 {
  font-family: "museo_sans100";
}
.M700 {
  font-family: "museo_sans700";
}
.RBTREG {
  font-family: "Roboto-Regular";
}
.RBLHT {
  font-family: "Roboto-Light";
}

.Cor1 {
  /* Permalink - use to edit and share this gradient: http://colorzilla.com/gradient-editor/#00c4ca+0,00e8b7+100 */
  background: #00c4ca; /* Old browsers */
  background: -moz-linear-gradient(
    left,
    #00c4ca 0%,
    #00e8b7 100%
  ); /* FF3.6-15 */
  background: -webkit-linear-gradient(
    left,
    #00c4ca 0%,
    #00e8b7 100%
  ); /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(
    to right,
    #00c4ca 0%,
    #00e8b7 100%
  ); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#00c4ca', endColorstr='#00e8b7',GradientType=1 ); /* IE6-9 */
}

.Cor2 {
  /* Permalink - use to edit and share this gradient: http://colorzilla.com/gradient-editor/#2e6ce8+1,30d7f4+94 */
  background: #2e6ce8; /* Old browsers */
  background: -moz-linear-gradient(
    left,
    #2e6ce8 1%,
    #30d7f4 94%
  ); /* FF3.6-15 */
  background: -webkit-linear-gradient(
    left,
    #2e6ce8 1%,
    #30d7f4 94%
  ); /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(
    to right,
    #2e6ce8 1%,
    #30d7f4 94%
  ); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#2e6ce8', endColorstr='#30d7f4',GradientType=1 ); /* IE6-9 */
}

.Cor3 {
  /* Permalink - use to edit and share this gradient: http://colorzilla.com/gradient-editor/#985fe8+28,fc55a0+100 */
  background: #985fe8; /* Old browsers */
  background: -moz-linear-gradient(
    left,
    #985fe8 28%,
    #fc55a0 100%
  ); /* FF3.6-15 */
  background: -webkit-linear-gradient(
    left,
    #985fe8 28%,
    #fc55a0 100%
  ); /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(
    to right,
    #985fe8 28%,
    #fc55a0 100%
  ); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#985fe8', endColorstr='#fc55a0',GradientType=1 ); /* IE6-9 */
}

/* fontes */
@font-face {
  font-family: "museo_sans900";
  src: url("assets/fonts/museosans-900-webfont.woff2") format("woff2"),
    url("assets/fonts/museosans-900-webfont.woff") format("woff");
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: "museo_sans500";
  src: url("assets/fonts/museosans_500-webfont.woff2") format("woff2"),
    url("assets/fonts/museosans_500-webfont.woff") format("woff");
  font-weight: normal;
  font-style: normal;
}
@font-face {
  font-family: "museo_sans100";
  src: url("assets/fonts/museosans-100-webfont.woff2") format("woff2"),
    url("assets/fonts/museosans-100-webfont.woff") format("woff");
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: "museo_sans300";
  src: url("assets/fonts/museosans-300-webfont.woff2") format("woff2"),
    url("assets/fonts/museosans-300-webfont.woff") format("woff");
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: "museo_sans700";
  src: url("assets/fonts/museosans-700_0-webfont.woff2") format("woff2"),
    url("assets/fonts/museosans-700_0-webfont.woff") format("woff");
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: "Roboto-Regular";
  src: url("assets/fonts/Roboto-Regular.eot?#iefix") format("embedded-opentype"),
    url("assets/fonts/Roboto-Regular.woff") format("woff"),
    url("assets/fonts/Roboto-Regular.ttf") format("truetype"),
    url("assets/fonts/Roboto-Regular.svg#Roboto-Regular") format("svg");
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: "Roboto-Light";
  src: url("assets/fonts/Roboto-Light.eot?#iefix") format("embedded-opentype"),
    url("assets/fonts/Roboto-Light.woff") format("woff"),
    url("assets/fonts/Roboto-Light.ttf") format("truetype"),
    url("assets/fonts/Roboto-Light.svg#Roboto-Light") format("svg");
  font-weight: normal;
  font-style: normal;
}
</style>

