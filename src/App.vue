<template>
  <Header />
  <div class="container mx-auto">
    <Main />
  </div>
</template>
<script>
import Header from './components/Header/Header.vue';
import Main from './components/Main/Main.vue';
export default {
  name: "App",
  components:{Header,Main}
};
</script>
<style lang="css"></style>
