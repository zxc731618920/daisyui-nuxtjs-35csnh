<template>
  <div class="p-4 m-4 flex flex-wrap justify-center items-center">
    <button class="btn btn-outline btn-accent">{{ props.msg1 }}</button>
  </div>
</template>

<script setup lang="ts">
const props = defineProps<{
  msg1: string;
}>();
</script>

<style lang="scss" scoped></style>
