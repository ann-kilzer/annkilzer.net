<template>
  <div>
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Header from "~/components/appshell/header.vue"
import Footer from "~/components/appshell/footer.vue"

export default Vue.extend({
  components: {
    Header,
    Footer
  }
});
</script>