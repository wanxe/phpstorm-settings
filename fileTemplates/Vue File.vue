<template>
    <div class="container">
        <h1>{{ msg }}</h1>
    </div>
</template>

<script>
  export default {
    data () {
      return {
        msg: 'hello vue'
      }
    },
    components: {}
  }
</script>

<style lang="css" scoped>
    body {
        background-color: #ff0000;
    }
</style>