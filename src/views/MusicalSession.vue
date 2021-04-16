<template>
  <div>
    <the-sessions-header title="Available Sessions"></the-sessions-header>
    <session-list :sessions="singSessions"></session-list>
  </div>
</template>

<script>
import SessionList from "@/components/SessionList.vue";
import TheSessionsHeader from "@/components/TheSessionsHeader.vue";

export default {
  components: {
    SessionList,
    TheSessionsHeader,
  },
  data() {
    return {
      singSessions: [
        {
          id: 1,
          title: "Laulu eka",
          desc: "Aloittelijalle",
          time: "Ti 20-21",
          place: "Zoom",
        },
        {
          id: 2,
          title: "Laulu toka",
          desc: "Kehittyneemmille",
          time: "Ke 18-19",
          place: "Zoom",
        },
        {
          id: 3,
          title: "Laulu toka",
          desc: "Kehittyneemmille",
          time: "To 19-20",
          place: "Työhuone",
        }
      ],
    };
  },
};
</script>