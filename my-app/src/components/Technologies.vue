<template>
  <div class="maintech">
    <div class="introduction">
        <h3>Below are some technologies I am familiar with</h3>
    </div>
    <div class="technologies">
      <div class="html">
        <img src="../assets/html.png" alt="HTML" class="image" />
      </div>

      <div class="css">
        <img src="../assets/css.png" alt="CSS" class="image" />
      </div>

      <div class="vuejs">
        <img src="../assets/js.png" alt="JavaScript" class="image" />
      </div>
    </div>
    <div class="technologies">
      <div class="nodejs">
        <img src="../assets/nodejs.png" alt="Node.js" class="image" />
      </div>

      <div class="reactjs">
        <img src="../assets/reactjs.png" alt="React.js" class="image" />
      </div>

      <div class="vuejs">
        <img src="../assets/vuejs.png" alt="Vue.js" class="image" />
      </div>
    </div>
    <div class="technologies">
      <div class="cpp">
        <img src="../assets/c++.png" alt="C++" class="image" />
      </div>

      <div class="java">
        <img src="../assets/Java-Logo.png" alt="Java" class="image" />
      </div>

      <div class="netcore">
        <img src="../assets/netcore.png" alt="ASP .NET Core" class="image" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Technologies",
};
</script>

<style scoped>
.maintech {
  display: block;
  text-align: center;
  padding-top: 20px;
}

.technologies {
  display: flex;
  text-align: center;
}

img {
  width: 70%;
  height: auto;
  vertical-align: middle;
}

.nodejs {
  flex: calc(1200 / 734);
}

.nodejs:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.vuejs {
  flex: calc(500 / 300);
}

.vuejs:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.reactjs {
  flex: calc(1613 / 501);
}

.reactjs:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.cpp {
  flex: 1;
}

.cpp:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.netcore {
  flex: 1;
}

.netcore:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.java {
  flex: calc(4000 / 2500);
}

.java:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.html {
  flex: calc(4000 / 2500);
}

.html:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.css {
  flex: calc(4000 / 2500);
}

.css:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.js {
  flex: calc(4000 / 2500);
}

.js:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}
</style>