<template>
  <div class="container-line">
    <div class="into">
      <div class="wrap">
        <div class="block">
          1
          <span class="dop-block" />
        </div>
        <div class="block">
          2
          <span class="dop-block" />
        </div>
        <div class="block">
          3
          <span class="dop-block" />
        </div>
      </div>
      <div class="line" />
    </div>
  </div>
</template>
<style scoped lang="scss">
  .container-line {
    margin: 60px 0
  }
  .line {
    background: #e7d04a;
    height: 150px;
    width: 100%;
  }
  .wrap {
    display: flex;
    justify-content: space-around;
    align-items: center;
    max-width: 900px;
    margin: 0 auto;
  }
  .block {
    color: #5c5652;
    font-family: Arial, sans-serif;
    font-weight: 700;
    font-size: 70px;
    padding: 20px 70px;
    border-top: 10px solid #e7d04a;
    border-right: 10px solid #e7d04a;
    border-left: 10px solid #e7d04a;
    position: relative;
  }
  .dop-block {
    position: absolute;
    height: 30px;
    border-bottom: 10px solid white;
    border-right: 10px solid white;
    border-left: 10px solid white;
    bottom: -40px;
    width: 100%;
    left: -10px;
  }

</style>