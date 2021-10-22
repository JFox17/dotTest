<template>
<div id="app">
  <div class="container">
    <IntoText />
    <Into />
    <IntoText />
  </div>
</div>
</template>
<script>
import Into from './components/Into.vue'
import IntoText from './components/IntoText.vue'

export default{
  name: 'app',
  components: { 
    Into,
    IntoText
  }
}
</script>
<style lang="scss">
  body {
    margin: 0;
  }
  .container {
    background: white;
    margin: 0 auto;
    max-width: 1140px
  }

</style>
