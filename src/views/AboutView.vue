<template>
  <div class="about">
    <Header/>
    <div id="about-info">
      <Menu/>
      <Main/>
    </div>
    <Footer/>
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