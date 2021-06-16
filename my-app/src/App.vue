<template>
  <div id="app">
    <Intro />
    <Technologies />
    <EmailForm />
  </div>
</template>

<script>
import Intro from "./components/Intro.vue";
import Technologies from "./components/Technologies.vue";
import EmailForm from "./components/EmailForm.vue";

export default {
  name: "App",
  components: {
    Intro,
    Technologies,
    EmailForm
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
  background-color: white;
}
</style>
