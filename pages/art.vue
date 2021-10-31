<template>
  <div>
    <div class="grid grid-flow-col grid-cols-3 grid-rows-3 gap-4">
      <div v-for="i in boxes" :key="i" container class="bg-blue-100 box-border h-32 w-32 p-4 border-4">{{i}}</div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
export default Vue.extend({
  data() {
    return {
      boxes: [1, 2, 3, 4, 5, 6, 7, 8, 9],
    };
  },
});
</script>