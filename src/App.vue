<template>

  <div class="container">
    <HeaderComp />
    <MainComp />
    <FooterComp />
  </div>
  
</template>

<script>
import FooterComp from './components/FooterComp.vue';
import HeaderComp from './components/HeaderComp.vue';
import MainComp from './components/MainComp.vue';


export default {
  name: 'App',
  components: {
    HeaderComp,
    MainComp,
    FooterComp,
  }
}
</script>

<style lang="scss">

@import './assets/style/vars';
@import './assets/style/vars';
@import './assets/style/vars'
</style>
