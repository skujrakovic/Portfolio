<template>
  <div class="container">
    <form class="forma">
      <label for="name">Full name: </label>
      <input type="text" name="name" id="name" />
      <label for="email">Email address: </label>
      <input type="text" name="email" id="email" />
      <label for="subject">Subject: </label>
      <input type="textarea" name="subject" id="subject" />
      <label for="message">Message: </label>
      <input type="textarea" name="message" id="message" />
    </form>
  </div>
</template>

<script>
export default {
  name: "EmailForm",
};
</script>

<style scoped>
.container {
  display: block;
}

#name {
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  width: 100%;
  line-height: 2;
}

#email {
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  width: 100%;
  line-height: 2;
}

#subject {
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  width: 100%;
  line-height: 2;
}

#message {
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  width: 100%;
  line-height: 10;
}
</style>
