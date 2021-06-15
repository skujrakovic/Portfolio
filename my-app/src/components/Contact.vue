<template>
  <div class="kontakt">
    <div class="email-forma">
      <EmailForm />
    </div>
    <div
      class="badge-base LI-profile-badge"
      data-locale="en_US"
      data-size="medium"
      data-theme="light"
      data-type="VERTICAL"
      data-vanity="samija-kujrakovic"
      data-version="v1"
    >
      <a
        class="badge-base__link LI-simple-link"
        href="https://ba.linkedin.com/in/samija-kujrakovic?trk=profile-badge"
      ></a>
    </div>
  </div>
</template>

<script>
import EmailForm from "./EmailForm.vue";
export default {
  name: "Contact",
  components: {
    EmailForm,
  },
};
</script>

<style scoped>
.kontakt {
  padding-top: 50px;
  display: flex;
  text-align: center;
}

.email-forma {
  width: 70%;
}

.badge-base {
  width: 30%;
  text-align: center;
}
</style>
