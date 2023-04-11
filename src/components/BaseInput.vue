<!-- eslint-disable prettier/prettier -->
<script setup>
  const props = defineProps({
    label: {
      type: String,
      default: ''
    }
  })
</script>

<template>
  <label>{{ label }}</label>
  <input 
    :placeholder="label"
    class="field"
  />
</template>

<style></style>
