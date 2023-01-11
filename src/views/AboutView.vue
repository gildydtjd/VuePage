<template>
  <div class="about">
    <Header></Header>
    <div id="about-info">
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
  name: "AboutView",
  components: {
    Header,
    Menu,
    Footer, 
    Main
  },
};
</script>
<style>
  #about-info{
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>