<template>
  <div id="app">
    <!-- header -->
    <HeaderComp1/>
    <!-- main -->
    <MainComp1/>
    <!-- footer -->
    <FooterComp1/>
    <FooterComp2/>
    
  </div>
</template>

<script>
import HeaderComp1 from '../components/Header/HeaderComp1.vue'
import MainComp1 from './components/Main/MainComp1.vue'
import FooterComp1 from '../components/Footer/FooterComp1.vue'
import FooterComp2 from "../components/Footer/FooterComp2.vue";
export default {
  name: 'App',
  components: {
    HeaderComp1,
    MainComp1,
    FooterComp1,
    FooterComp2,
    
  }
}
</script>

<style lang="scss">
*{
  list-style: none;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  
}
</style>