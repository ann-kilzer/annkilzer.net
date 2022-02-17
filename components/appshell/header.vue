<template>
  <div class="container w-max flex flex-wrap m-4">
    <div class="grid grid-cols-4 gap-8">
      <a href="/"><span class="font-bold hover:text-sky-500">Ann Kilzer</span></a>
      <nav v-for="link in links" :key="link.name">
        <a :href="link.path" class="m-2 font-semibold hover:text-violet-500">{{ link.name }}</a>
      </nav>
    </div>
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