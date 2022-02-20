<template>
  <a
    target="_blank"
    :href="href"
    class="underline text-emerald-700 hover:text-emerald-500"
    ><slot />
  </a>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  props: {
    href: { type: String, required: true },
  },
});
</script>
