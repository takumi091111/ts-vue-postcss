<template>
  <p>Hello, Vue</p>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  name: 'hello'
})
</script>

<style lang="postcss" scoped>
p {
  &:hover {
    color: hotpink;
  }
  color: red;
}
</style>
