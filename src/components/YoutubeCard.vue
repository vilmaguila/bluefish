<template>
  <md-card md-with-hover>
    <md-card-header>
      <div class="md-title">{{ title }}</div>
      <div class="md-subhead">{{ artist }}</div>
    </md-card-header>

    <md-card-media>
      <iframe
        :src="src"
        frameborder="0"
      ></iframe>
    </md-card-media>

    <md-card-content> {{ desc }} </md-card-content>
  </md-card>
</template>

<script>
export default {
  name: 'YoutubeCard',
  props: ['title', 'artist', 'src', 'desc']
};
</script>

<style scoped>
  .md-card {
    width: 320px;
    margin: 4px;
    display: inline-block;
    vertical-align: top;
}
</style>