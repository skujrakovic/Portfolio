<template>
    <div class="technologies">
        <div class = "nodejs">
            <img src="../assets/nodejs.png" alt="Profile photo" class="image" />
        </div>

        <div class = "vuejs">
            <img src="../assets/vuejs.png" alt="Profile photo" class="image" />
        </div>

        <div class = "reactjs">
            <img src="../assets/reactjs.png" alt="Profile photo" class="image" />
        </div>

        <div class = "cpp">
            <img src="../assets/c++.png" alt="Profile photo" class="image" />
        </div>

        <div class = "java">
        <img src="../assets/Java-Logo.png" alt="Profile photo" class="image" />
        </div>

        <div class = "netcore">
        <img src="../assets/netcore.png" alt="Profile photo" class="image" />
        </div>
    </div>
</template>

<script>
export default {
  name: 'Technologies'
}
</script>

<style scoped>
.technologies {
    display: flex;
    text-align: center;
    padding-top: 20px;
}

img {
    width: 70%;
    height: auto;
    vertical-align: middle;
}

.nodejs {
    flex: calc(1200/734);
}

.nodejs:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.2);
}

.vuejs {
    flex: calc(500/300);
}

.vuejs:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.2);
}

.reactjs {
    flex: calc(1613/501);
}

.reactjs:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.2);
}

.cpp {
    flex: 1;
}

.cpp:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.2);
}

.netcore {
    flex: 1;
}

.netcore:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.2);
}

.java {
    flex: calc(4000/2500);
}

.java:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.2);
}
</style>