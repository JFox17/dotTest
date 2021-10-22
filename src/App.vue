<template>
<div id="app">
  <h3 class="text">{{text}}</h3>
  <p>Текст</p>

</div>
</template>
<script>
export default{
  name: 'app',
  data() {
    return {
      text: 'Welcome'
    }
  }
}
</script>
<style scoped lang="scss">
  #app {
    color:red;
  }
  .text{
    color: green;
  }

</style>