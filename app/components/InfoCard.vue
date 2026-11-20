<script setup>
defineProps({
  title: String,
  description: String
})
</script>

<template>
  <div class="bg-[#F7D6C4]/30 p-6 rounded-xl border border-[#F7D6C4]">
    <h3 class="font-bold text-[#1E253C] text-lg mb-2">{{ title }}</h3>
    <p class="text-[#506183] text-sm leading-relaxed">{{ description }}</p>
  </div>
</template>