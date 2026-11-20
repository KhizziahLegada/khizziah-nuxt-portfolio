<script setup>
defineProps({
  label: String,
  color: {
    type: String,
    default: 'bg-[#1E253C] text-white'
  }
})
</script>

<template>
  <button :class="`px-6 py-2 rounded-lg font-bold shadow-md hover:opacity-80 transition-opacity ${color}`">
    {{ label }}
  </button>
</template>