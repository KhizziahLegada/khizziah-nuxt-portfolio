
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
  <button
    :class="`px-7 py-3 text-sm tracking-wide rounded-md
    shadow-sm hover:-translate-y-1 hover:shadow-lg
    transition-all duration-300 ${color}`"
  >
    {{ label }}
  </button>
</template>
