<template>
  <div>
    <slot></slot>
  </div>
</template>
<script setup>
import { useSlots } from "vue";
const slots = useSlots();
const res = slots.default();
debugger
</script>
<style></style>
