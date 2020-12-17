<template>
  <div id="app">
  <router-view></router-view>
<main-tab-bar></main-tab-bar>
<!--  <MainTabBar></MainTabBar>-->
  </div>
</template>
<script>
import MainTabBar from "components/content/maintabbar/MainTabBar";

export default {
  name: 'App',
  components: {
    name: 'app',
    components: {
      MainTabBar
    }
  }
}
</script>
<style>

</style>
