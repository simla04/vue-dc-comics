<template>
  <div class="box flex">
      <img class="size-img img" src="../../assets/img/buy-comics-digital-comics.png" alt="">
      <h3>DIGITAL COMICS</h3>
      <img class="size-img" src="../../assets/img/buy-comics-merchandise.png" alt="">
      <h3>DC MERCHANDAISE</h3>
      <img class="size-img" src="../../assets/img/buy-comics-subscriptions.png" alt="">
      <h3>SUBSCRIPTION</h3>
      <img class="size-img" src="../../assets/img/buy-comics-shop-locator.png" alt="">
      <h3>COMIC SHOP LOCATOR</h3>
      <img class="size-img" src="../../assets/img/buy-dc-power-visa.svg" alt="">
      <h3>DC POWER VISA</h3>
  </div>
</template>

<script>
  export default {
      name:"MainOne",
      
  }
</script>

<style lang="scss" scoped>
  .box{
      width: 100%;
      background-color: #0C7CEC;
      padding: 50px;
      align-items: center;
      justify-content: center;
      position: relative;
      z-index: 1;
      
  }
  .size-img{
      width: 60px;
  }
  .flex{
      display: flex;
  }
  h3{
      margin: 0 50px;
      color:white;
  }
  .img{
      margin-left: 100px;
  }
</style>