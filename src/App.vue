<template>
  <div id="app">
      <Header />
      <First-Section />
      <Second-Section />
      <Footer />
      <Bottom-Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import FirstSection from "./components/FirstSection.vue";
import SecondSection from "./components/SecondSection.vue";
import Footer from "./components/Footer.vue";
import BottomFooter from "./components/BottomFooter.vue";
export default {
  name: "App",
  components: {
    Header,
    FirstSection,
    SecondSection,
    Footer,
    BottomFooter
  },
};
</script>

<style>
#app {
  margin: auto;
  
}


/* RESET */

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style-type: none;
}

 .container {
        height: 100px;
      
    }
</style>
