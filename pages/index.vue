<template>
  <container title="Hello!">
    <p class="my-4">
      My name is Ann Kilzer. I'm a polymath, and my career is in software
      engineering. I currently work at
      <weblink href="https://www.mercari.com">Mercari</weblink>
      on the Trust &amp; Safety team.
    </p>
    <p class="my-4">
      I received my Master's in Computer Science from the University of Texas at
      Austin, where I spent a few years researching privacy. I grew up in
      Missoula, Montana, and attended college at Gonzaga University, where I
      majored in computer science, math, and art. I moved to Tokyo in early 2018
      with no job, just an eager dream of living abroad. In my spare time, I
      enjoy Japanese Calligraphy 書道, Nihonga painting 日本画, cooking, hiking, 
      and riding slow trains around Japan.
    </p>
    <p class="my-4">
      初めまして！杏キルザーです。
      私は多趣味な人間で、キャリアはソフトウェアです。
      今は
      <weblink href="https://www.mercari.com">メルカリ</weblink>
      の「Trust &amp; Safety」チームで働きます。
    </p>

    <p class="my-4">
      テキサス大学オースティン校でコンピュータサイエンスの修士号を取得し、数年間プライバシーの研究に従事した後、現在に至る。
      私の出身はミズラ市モンタナ。
      「Gonzaga]大学では、コンピューターサイエンス、数学、アートを学びました。
      2018年に東京に移住しました。
      趣味は書道、日本画、料理、ハイキング、鉄道に乗ること。

      
    </p>
    <p>
      よろしくお願いします。
    </p>
  </container>
</template>

<script lang="ts">
import Vue from "vue";
import container from "~/components/appshell/container.vue";
import weblink from "~/components/weblink.vue"

export default Vue.extend({
  components: {
    container,
    weblink,
  },
});
</script>
