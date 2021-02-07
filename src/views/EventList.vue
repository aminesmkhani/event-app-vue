<template>
  <div>
    <h1>EventList</h1>
    <EventCart/>
  </div>
</template>

<script>
import EventCart from "@/components/EventCart";
export default {
  name: "EventList",
  components: {
    // eslint-disable-next-line vue/no-unused-components
    EventCart
  }
};
</script>

<style scoped></style>
