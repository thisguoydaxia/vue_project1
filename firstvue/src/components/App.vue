<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>{{ msg }}</h1>
    <firstcomponent></firstcomponent>
  </div>
</template>

<script>
  import firstcomponent from './component/firstcomponent.vue'

  export default {
    data () {
      return {
        msg: 'Hello Vue!'
      }
    },
    components: { firstcomponent }
    }
</script>

<style scoped>

</style>
