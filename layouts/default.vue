<template>
  <div>
    <Header />
    <div class="container w-max flex m-4">
      <Nuxt />
    </div>
    <Footer />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Header from "~/components/appshell/header.vue";
import Footer from "~/components/appshell/footer.vue";

export default Vue.extend({
  components: {
    Header,
    Footer,
  },
});
</script>
