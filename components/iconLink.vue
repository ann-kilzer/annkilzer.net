<template>
  <a
    :href="href"
    :aria-label="name"
    class="hover:text-violet-500 text-zinc-700 text-xl"
  >
    <font-awesome-icon :icon="['fab', icon]" class="h-5 w-5" />
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
