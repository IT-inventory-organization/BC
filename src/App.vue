<template>
  <div id="app">
    <!-- <core-app-bar></core-app-bar> -->
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {
    CoreAppBar: () => import('@/components/base/AppBar')
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
