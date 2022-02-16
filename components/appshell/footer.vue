<template>
  <div class="container w-max flex mx-4 my-8">
    <div class="grid gap-4 grid-cols-6">
      <icon-link
        name="GitHub"
        href="https://github.com/ann-kilzer"
        icon="fa-brands fa-github"
      />
      <icon-link
        name="Twitter"
        href="https://twitter.com/stonecoldkilzer"
        icon="fa-brands fa-twitter"
      />
      <icon-link
        name="LinkedIn"
        href="https://www.linkedin.com/in/annkilzer/"
        icon="fa-brands fa-linkedin-in"
      />
      <icon-link
        name="Instagram"
        href="https://www.instagram.com/cat_bacon/"
        icon="fa-brands fa-instagram"
      />
      <icon-link
        name="Medium"
        href="https://medium.com/@annkilzer"
        icon="fa-brands fa-medium"
      />
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import iconLink from "../iconLink.vue";

export default Vue.extend({
  components: { iconLink },
  data() {
    return {};
  },
});
</script>