<template>
  <button @click="onButtonClick()" class="test" :style="{ background: color }">
    {{ text }}
  </button>
</template>

<script>
export default {
  name: 'Button',
  props: {
    text: String,
    color: String,
  },
  methods: {
    onButtonClick() {
      console.log('object');
    },
  },
};
</script>

<style>
.test {
  padding: 10px;
  border: none;
  border-radius: 5px;
}
</style>
