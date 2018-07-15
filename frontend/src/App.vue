<template>
  <div id="app">
    <div id="header">
      <main-header/>
    </div>

    <img src="./assets/img/logo.png">
    <router-view/>

    <div id="footer">
      <main-footer/>
    </div>
  </div>
</template>

<script>

import MainHeader from './shared-components/MainHeader.vue'
import MainFooter from './shared-components/MainFooter.vue'

export default {
  name: 'App',
  components: {
    'main-header': MainHeader,
    'main-footer': MainFooter
  }
}

</script>

<style>
  @import './assets/css/demo.css'
</style>
