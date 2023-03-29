<template>
  <Header />
    <Main />
    <About />
    <Blog />
    <Footer />
</template>
<script>
import Header from './components/Header/Header.vue';
import Main from './components/Main/Main.vue';
import Footer from './components/Footer/Footer.vue';
import About from './components/About/About.vue';
import Blog from './components/Blog/Blog.vue';
export default {
  name: "App",
  components:{Header,Main,Footer,About,Blog}
};
</script>
<style lang="css" scoped>
  .main {
    height: calc(100vh - 70px - 70px);
  }
</style>
