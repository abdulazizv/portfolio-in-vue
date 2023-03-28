<template>
  <Header />
  <div class="container mx-auto main">
    <Main />
  </div>
  <Footer />
</template>
<script>
import Header from './components/Header/Header.vue';
import Main from './components/Main/Main.vue';
import Footer from './components/Footer/Footer.vue';
export default {
  name: "App",
  components:{Header,Main,Footer}
};
</script>
<style lang="css" scoped>
  .main {
    height: calc(100vh - 70px - 70px);
  }
</style>
