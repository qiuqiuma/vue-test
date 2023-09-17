<script setup lang="ts">
import Test from './compoents/Test.vue'
const arr = [1,2,3]
</script>

<template>
  <div>
          <!-- <div>1</div>
      <div>2</div>
      <div>3</div> -->
    <Test>
      <div v-for="(item,index) in arr" :key="index"> {{ item }}</div>
    </Test>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
