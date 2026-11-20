
<script setup>
defineProps({
  title: String,
  description: String
})
</script>

<template>
  <article class="bg-[#F7D6C4]/30 border border-[#F7D6C4]
                  p-8 rounded-xl hover:bg-[#F7D6C4]/50
                  transition-colors duration-300">

    <div class="text-[#A68C7A] text-xs tracking-[3px] mb-6">
      LEARN MORE
    </div>

    <h3 class="font-serif text-2xl text-[#1E253C] mb-4">
      {{ title }}
    </h3>

    <p class="text-sm text-[#506183] leading-7">
      {{ description }}
    </p>

  </article>
</template>
