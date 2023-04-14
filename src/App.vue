<script>
  import SiteHeader from "./components/SiteHeader.vue"
  import SiteBanner from "./components/SiteBanner.vue"
  import SiteMain from "./components/SiteMain.vue"
  import SiteFooterTop from "./components/SiteFooterTop.vue"
  import SiteFooterBottom from "./components/SiteFooterBottom.vue"

  export default {
    components: {
      SiteHeader,
      SiteMain,
      SiteFooterTop,
      SiteFooterBottom,
      SiteBanner,
    }
  }
</script>

<template>

  <!-- header section -->
  <SiteHeader></SiteHeader>

  <!-- main section -->
  <SiteMain></SiteMain>

  <!-- banner section -->
  <SiteBanner></SiteBanner>

  <!-- footer top section -->
  <SiteFooterTop></SiteFooterTop>

  <!-- footer bottom section -->
  <SiteFooterBottom></SiteFooterBottom>


</template>

<style lang="scss">

</style>
