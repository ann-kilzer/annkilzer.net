<template>
  <container title="Hello!">
    <div class="mb-4 sm:ml-4">
      <img
        class="sm:float-right sm:w-1/3"
        src="@/static/ann-kilzer.jpg"
        alt="Ann Kilzer wearing a green coat and standing in front of a concrete wall"
      >
    </div>
    <div class="">
      <p class="my-4 max-w-prose">
        My name is Ann Kilzer. I'm a polymath, and my career is in software
        engineering. I currently work at
        <weblink href="https://www.mercari.com">
          Mercari
        </weblink>
        on the Trust &amp; Safety team.
      </p>
      <p class="my-4 max-w-prose">
        I received my Master's in Computer Science from the University of Texas
        at Austin, where I spent a few years researching privacy. I grew up in
        Missoula, Montana, and attended college at Gonzaga University, where I
        majored in computer science, math, and art. I moved to Tokyo in early
        2018 with no job, just an eager dream of living abroad. In my spare
        time, I enjoy Japanese Calligraphy 書道, Nihonga painting 日本画,
        cooking, hiking, and riding slow trains around Japan.
      </p>
      <p class="my-4 max-w-prose">
        初めまして！杏キルザーです。
        私は多趣味な人間で、職業はソフトウェアエンジニアです。 今は
        <web-link href="https://www.mercari.com">
          メルカリ
        </web-link>
        の「Trust &amp; Safety」チームで働いています。
      </p>

      <p class="my-4 max-w-prose">
        私はミズラー市モンタナ出身で、ゴンザガ大学に進学しコンピューターサイエンス、数学、アートを学びました。
        また、テキサス大学オースティン校で数年間プライバシーについての研究に従事し、コンピュータサイエンスの修士号を取得しました。
        その後、2018年に東京に移住し、現在に至ります。
        趣味は書道、日本画、料理、ハイキング、電車に乗ることです。
      </p>
      <p class="my-4 max-w-prose">
        よろしくお願いします。
      </p>
    </div>
  </container>
</template>

<script lang="ts">
import Vue from "vue";
import container from "~/components/appshell/container.vue";
import webLink from "~/components/webLink.vue";

export default Vue.extend({
  components: {
    container,
    webLink,
  },
});
</script>
