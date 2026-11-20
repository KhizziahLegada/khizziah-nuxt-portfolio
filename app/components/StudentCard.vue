<script setup>
defineProps({
  name: String,
  course: String,
  year: String
})
</script>

<template>
  <div class="bg-white p-6 rounded-2xl shadow-lg border border-[#A6B1C2]/40">
    <h2 class="text-2xl font-serif font-bold text-[#1E253C] mb-2">{{ name }}</h2>
    <p class="text-[#506183]"><strong>Course:</strong> {{ course }}</p>
    <p class="text-[#506183]"><strong>Year:</strong> {{ year }}</p>
  </div>
</template>