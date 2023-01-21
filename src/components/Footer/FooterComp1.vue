<template>
  <div class="box">
    <div class="flex">
      <div class="margin-lists">
        <h4>DC COMICS</h4>
        <ul>
          <li>Character</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
        </ul>
        <h4>SHOP</h4>
        <ul>
          <li>Shop DC</li>
          <li>Shop DC Collectibles</li>
        </ul>
      </div>
      <div class="margin-lists">
        <h4>DC</h4>
        <ul>
          <li>Terms of use</li>
          <li>Privacy policy (New)</li>
          <li>Ad Choices</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshop</li>
          <li>CPSC Certificates</li>
          <li>Rating</li>
          <li>Shop Help</li>
          <li>Contact Us</li>
        </ul>
      </div>
      <div class="margin-lists">
        <h4>SITES</h4>
        <ul>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>
      </div>
    </div>

    <div>
      <img src="../../assets/img/dc-logo-bg.png" alt="" />
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterComp1",
};
</script>

<style lang="scss" scoped>
.box {
  display: flex;
  background-image: url(../../assets/img/footer-bg.jpg);
  background-size: cover;
  justify-content: space-around;
  align-items: center;
  max-height: 500px;
  position: relative;
}
img {
  justify-self: end;
}
li {
  color: gray;
  line-height: 25px;
}
h4 {
  margin: 20px 0;
  color: white;
}
.margin-lists {
  margin-right: 50px;
}
.flex {
  display: flex;
}
</style>
