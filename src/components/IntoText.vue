<template>
  <div class=container-text>
     <div class="block-text">
      <p>{{text}}</p>
      <p>{{text}}</p>
      <p>{{text}}</p>
      <p>{{text}}</p>
      <p>{{text}}</p>
      <p>{{text}}</p>
      <p>{{text}}</p>
      <p>{{shortText}}</p>
    </div>
  </div>
</template>

<script>
  export default{
    name: 'app',
    data() {
      return {
        text: 'текст текст текст текст текст текст текст текст текст текст текст текст текст текст текст текст текст текст текст текст текст текст текст текст текст текст',
        shortText:'текст текст текст текст текст текст текст текст текст текст текст текст текст текст текст текст текст текст'
      }
    }
  }
</script>

<style scoped lang="scss">
  .container-text {
    margin: 0 auto;
  }
  .block-text {
    color: black;
    font-family: Arial, sans-serif;
    font-weight: 300;
    font-size: 14px;
    line-height: 24px;
    padding: 50px 0;
  }
  .block-text > p {
    margin: 0
  }

</style>
