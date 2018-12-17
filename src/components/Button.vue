<template>
  <div><slot></slot></div>
</template>

<script>
export default {
  name: 'Button',
};
</script>

<style scoped>
div {
  display: inline-block;
  border-radius: 4px;
  border: solid 2px white;
  padding: 10px;
  font-weight: bold;
}
div:hover {
  background: rgba(0,0,0,0.5);
  cursor: pointer;
}
</style>
