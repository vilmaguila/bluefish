<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <youtube-card
      title="Juokse vaan"
      artist="Punomo"
      src="https://www.youtube.com/embed/vnjc2q4dTKo"
      desc="'Juokse vaan' on Punomon..."
    ></youtube-card>
    <youtube-card
      title="Siskot"
      artist="Punomo"
      src="https://www.youtube.com/embed/xLEXmApp5Iw"
      desc="'Siskot' on Punomon..."
    ></youtube-card>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import YoutubeCard from "@/components/YoutubeCard.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    YoutubeCard,
  },
};
</script>
