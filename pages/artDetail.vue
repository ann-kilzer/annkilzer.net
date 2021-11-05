<template>
  <div>
    <h1>{{name}}</h1>
    <img src="http://placekitten.com/700/500" />
    <span>{{date}}</span><br>
    <span>{{medium}}</span><br>
    <span>{{about}}</span>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
export default Vue.extend({
  data() {
    return {
      name: "Artwork name",
      date: "2020",
      medium: "oil on canvas",
      about: "about",
    };
  },
});
</script>