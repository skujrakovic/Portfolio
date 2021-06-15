<template>
  <div class="introduction">
    <div class="container">
      <img src="../assets/profile-photo.jpg" alt="Profile photo" class="image" />
    </div>
    <h1>
      <span>Hi, </span> 
      <span>my name is Samija</span>
    </h1>
    <p>I am a Bachelor of Engineering, Computer Science and Informatics.</p>
    <p>I have a diverse set of skills, ranging from frontend development using React.js and Vue.js to backend using Node.js</p>
    <p>I love learning and creating new things.</p>
  </div>
</template>

<script>
export default {
  name: 'Intro'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.introduction {
    background-color: #800020;
    height: 96vh;
    position: relative;
    backface-visibility: hidden;
    clip-path: polygon(0% 0%, 100% 0%, 100% 60%, 50% 100%, 0% 60%);

}
h1 {
  margin: 40px 0 0;
  letter-spacing: 15px;
  animation: move-up 2s ease-out;
}

p {
  margin: 15px 0 0;
  font-size: 18px;
  animation: move-up 2s ease-out 1s;
  animation-fill-mode: backwards;
}

h1,p {
  text-align: center;
  color:whitesmoke;
  display: block;
}

.container {
  margin-top: 10px;
  position: relative;
  width: 20%;
  margin: auto;
  backface-visibility: hidden;
}

.image {
  opacity: 1;
  display: block;
  width: 100%;
  height: auto;
  transition: 0.5s ease;
  backface-visibility: hidden;
  text-align: center;
  border-radius: 50%;
  animation: move-up 2s ease-out;
  padding-top: 20px;
}

@keyframes fade-in {
  0% {
    opacity: 0;
  }

  100% {
    opacity: 100;
  }
}

@keyframes move-up {
  0% {
    opacity: 0;
    transform: translateY(30px);
  }

  80% {
    transform: translateY(-10px);
  }

  100%{
    opacity:100;
    transform: translateY(0px);
  }
}

</style>
