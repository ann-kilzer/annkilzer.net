<template>
  <div class="container">
    <h1 class="text-2xl font-semibold mb-4">
      {{ title }}
    </h1>
    <slot />
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  props: {
    title: String,
  },
  data() {
    return {};
  },
});
</script>