<template>
  <div class="home">
    <Header></Header>
    <div id="home-info">
      <Menu></Menu>
      <Main></Main>
    </div>
    <Footer></Footer>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Menu from "@/components/Menu.vue";
import Footer from "@/components/Footer.vue";
import Main from "@/components/Main.vue";

export default {
  name: "HomeView",
  components: {
    Header,
    Menu,
    Footer,
    Main
  },
};
</script>

<style>
  #home-info{
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>
