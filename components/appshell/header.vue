<template>
  <div class="container w-max flex m-4 justify-between">
    <a href="/"><span>Ann Kilzer</span></a>
    <nav v-for="link in links" :key="link.name">
      <a :href="link.path" class="m-2">{{ link.name }}</a>
    </nav>
  </div>
</template>


<script lang="ts">
import Vue from "vue";
export default Vue.extend({
  data() {
    return {
      links: [
        { name: "Software", path: "/software" },
        { name: "Fine Art", path: "/art" },
      ],
    };
  },
});
</script>