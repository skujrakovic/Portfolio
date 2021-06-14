<template>
  <div id="app">
    <Intro />
    <Technologies />
    <Contact />
  </div>
</template>

<script>
import Intro from "./components/Intro.vue";
import Technologies from "./components/Technologies.vue";
import Contact from "./components/Contact.vue";

export default {
  name: "App",
  components: {
    Intro,
    Technologies,
    Contact
  },
};
</script>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
#app {
  padding: 30px;
  font-family: "Lato", sans-serif;
    font-weight: 400;
    font-size: 16px;
    line-height: 1.7;
}
</style>
