<template>
  <div id="count">
    <div>
      <hr />
      <h1>Count.vue : {{count}}</h1>
      <p>{{todos}}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "count",
  components: {},
  computed: {
    count() {
      return this.$store.state.count;
    },
    todos() {
      return this.$store.state.todos;
    }
  }
};
</script>

<style>
</style>
