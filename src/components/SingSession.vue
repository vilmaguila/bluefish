<template>
  <div>
    <md-card md-with-hover>
      <md-card-header>
        <div class="md-title">{{ title }}</div>
      </md-card-header>

      <md-card-content>
        {{ desc }}<br>
        {{ time }}<br>
        {{ place }}
      </md-card-content>

      <md-card-actions>
        <md-button>Action</md-button>
        <md-button>Action</md-button>
      </md-card-actions>
    </md-card>
  </div>
</template>

<script>
export default {
  name: 'SingSession',
  props: ['title', 'desc', 'time', 'place']
}
</script>

<style>
</style>