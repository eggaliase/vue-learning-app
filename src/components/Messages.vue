<template>
  <div>
    <h4>Messages</h4>
    <ul v-for="message in messages" v-bind:key="message.key">
      <li>{{ message }}</li>
    </ul>
  </div>
</template>
<script>
export default {
  data() {
    return {
      messages: ["1", "3", "its working"],
    };
  },
};
</script>