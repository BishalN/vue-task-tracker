<template>
  <h1>This is the header component {{ title }}</h1>
</template>

<script>
export default {
  name: 'Header',
  props: {
    title: { type: String, required: false, default: 'No title given' },
  },
};
</script>

<style scoped>
h1 {
  color: aquamarine;
  font-family: cursive;
}
</style>
