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
}

img {
    width: 70%;
    height: auto;
    vertical-align: middle;
}

.nodejs {
    flex: calc(1200/734);
}

.vuejs {
    flex: calc(500/300);
}

.reactjs {
    flex: calc(1613/501);
}

.cpp {
    flex: 1;
}

.netcore {
    flex: 1;
}

.java {
    flex: calc(4000/2500);
}
</style>