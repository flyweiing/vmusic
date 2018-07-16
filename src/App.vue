<template>
  <div id="app">
    <m-header></m-header>
    <!--<tab></tab>-->
    <router-view></router-view>
  </div>
</template>

<script type="text/ecmascript-6">
import MHeader from 'components/m-header/m-header'
//import Tab from 'components/m-header/m-header'

export default {
  name: 'App',
  components: {
    MHeader
  }
}
</script>

<style>
</style>
