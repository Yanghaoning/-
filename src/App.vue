<template>
  <div id="app">
    <router-view/>
    <FooterGuide v-show="$route.meta.showFooter"/>
  </div>
</template>

<script>
  import FooterGuide from './components/FooterGuide'
  export default {
    components: {
      FooterGuide
    }
  }
</script>

<style lang="less">

</style>
