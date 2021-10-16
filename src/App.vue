<template>
  <div id="app">
    <Card>
      <template #image>
        <img src="https://picsum.photos/id/1015/300" />
      </template>
      <template #title>
        <h2>Sending all my love from Vacation!</h2>
      </template>
      <template #description>
        <p>Please send someone to resuce me.</p>
        <p>Lost at Sea in Paradise!</p>
      </template>
    </Card>
  </div>
</template>
<script>
import Card from "./components/Card.vue";
export default {
  components: {
    Card,
  },
};
</script>
