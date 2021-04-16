<template>
  <ul>
    <sing-session
      v-for="item in sessions"
      :key="item.id"
      :title="item.title"
      :desc="item.desc"
      :time="item.time"
      :place="item.place"
    ></sing-session>
  </ul>
</template>

<script>
import SingSession from "@/components/SingSession.vue";

export default {
  name: 'SessionList',
  props: ['sessions'],
  components: {
    SingSession
  },
};
</script>