<template>
  <div>
    <p>いいね({{ testCase }})</p>
    <button @click="increment">+1</button>
  </div>
</template>

<script>
export default {
  props: ['testCase'],
  methods: {
    increment() {
      this.number += 1;
    },
  },
};
</script>

<style scoped>
div {
  border: 1px solid red;
}
</style>
