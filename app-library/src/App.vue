<template>
  <div id="app">
    <Home/>
  </div>
</template>

<script>
// @ is an alias to /src
import Home from '@/views/Home.vue'

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>
<style lang="scss">
#app {
  text-align: center;
  background-color: beige;
}

body {
  margin: 0;
}
</style>
