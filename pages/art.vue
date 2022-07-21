<template>
  <container title="Fine Art">
    <div class="grid grid-flow-col grid-cols-3 grid-rows-3 gap-4">
      <div
        v-for="i in images"
        :key="i.name"
        container
        class="border-yellow-200 box-border border-4"
      >
        <img v-bind:src="imagePath(i.file)" />
      </div>
    </div>
  </container>
</template>

<script>
import Vue from "vue";
import Container from "~/components/appshell/container.vue";

export default Vue.extend({
  components: {
    Container,
  },
  data() {
    return {
      images: [
        {
          name: "Tattoo Peony",
          year: "2021",
          file: "Tattoo Peony.jpg",
        },
        {
          name: "Magnolia",
          year: "2021",
          file: "Magnolia.jpg",
        },
        {
          name: "Taiyaki",
          year: "2021",
          file: "taiyaki.jpg",
        },
      ],
    };
  },
  methods: {
    imagePath(file) {
      return `${window.location.origin}/${file}`;
    },
  },
});
</script>
