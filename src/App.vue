<template>
  <div class="app">
    <h1>我是App.vue</h1>
    <p>{{ a }}</p>
  </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue'
const a = ref('hhh')
</script>

<style lang="scss" scoped>
.app {
  height: 500px;
  background-color: hotpink;
  h1 {
    color: skyblue;
  }
}
</style>
