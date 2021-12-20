<template>
  <div id="app">
      <Header />
      <First-Section />
  </div>
</template>

<script>
import FirstSection from "./components/FirstSection.vue";
import Header from "./components/Header.vue";
export default {
  name: "App",
  components: {
    Header,
    FirstSection
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

</style>
