<template>
  <container title="Fine Art">
    Coming soon :)
    <div class="grid grid-flow-col grid-cols-3 grid-rows-3 gap-4">
      <div v-for="i in boxes" :key="i" container class="border-yellow-200 box-border border-4">
        <img src="http://placekitten.com/300/300"/>
      </div>
    </div>
  </container>
</template>

<script lang="ts">
import Vue from "vue";
import Container from "~/components/appshell/container.vue";

export default Vue.extend({
  components: {
    Container,
  },
  data() {
    return {
      boxes: [1, 2, 3, 4, 5, 6, 7, 8, 9],
    };
  },
});
</script>