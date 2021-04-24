<template>
  <h1>This is the header component {{ title }}</h1>
  <Button text="hello" color="grey" />
</template>

<script>
import Button from './Button.vue';
export default {
  name: 'Header',
  props: {
    title: { type: String, required: false, default: 'No title given' },
  },
  components: {
    Button,
  },
};
</script>

<style scoped>
h1 {
  color: aquamarine;
  font-family: cursive;
}
</style>
