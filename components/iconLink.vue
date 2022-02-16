<template>
  <a :href="href" :aria-label="name">
    <font-awesome-icon :icon="icon" />
  </a>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  props: {
    name: String,
    href: String,
    icon: String, // denoted by font awesome classes
  },
  data() {
    return {};
  },
});
</script>