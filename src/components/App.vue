<script>
  import vueRecord from './vue-record.vue'

  export default {
    components: {
      vueRecord,
    },
  }
  
</script>
<template lang="pug">
    h1 Pug - node template engine
</template>
<template lang="pug">
div(id="app")
  vue-record(@record:start="")
</template>

<style>
  body {
    text-align: center;
    font-family: Helvetica, sans-serif;
  }
</style>
