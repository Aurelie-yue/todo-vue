<template>
  <div class="app-root">
    <TodoLists />
  </div>
</template>

<script setup>
import TodoLists from './components/TodoLists.vue'
</script>

<style>
.app-root {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #f6f6f6;
  padding: 40px 20px;
}
</style>