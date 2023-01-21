<template>
  <div>
      <div class="last-box flex">
      <div>
          <button>SIGN-UP NOW!</button>
      </div>
      <div class="flex">
          <h2>FOLLOW US</h2>
          <img src="../../assets/img/footer-facebook.png" alt="">
          <img src="../../assets/img/footer-twitter.png" alt="">
          <img src="../../assets/img/footer-youtube.png" alt="">
          <img src="../../assets/img/footer-pinterest.png" alt="">
          <img src="../../assets/img/footer-periscope.png" alt="">
      </div>
      
      
  </div>
  <div class="box2">
          
  </div>
  </div>
  
</template>

<script>
  export default {
      name:"FooterComp2",
  }
</script>

<style lang="scss" scoped>
  .last-box{
      background-color: rgb(65, 65, 65);
      width: 100%;
      height: 100px;
      position: relative;
      padding: 0 200px;
      
  }
  button{
      border: 1px solid #0C7CEC;
      background-color: rgb(65, 65, 65);
      color: white;
      font-size: 1.2rem;
      padding:10px
  }
  .flex{
      display: flex;
      align-items: center;
      justify-content: space-between;
  }
  h2{
      color:#0C7CEC
  }
  img{
      margin: 0 13px;
  }
  .box2{
      background-color: black;
      height:60px;
  }
 