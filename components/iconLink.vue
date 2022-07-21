<template>
  <a :href="href" :aria-label="name" class="hover:text-violet-500">
    <!--<font-awesome-icon :icon="icon" />-->
  </a>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  props: {
    name: { type: String, required: true },
    href: { type: String, required: true },
    icon: {
      type: String, // denoted by font awesome classes
      required: true,
    },
  },
  data() {
    return {};
  },
});
</script>
