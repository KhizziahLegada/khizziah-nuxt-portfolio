
<template>
  <header class="bg-[#1E253C] text-[#FCF8F2]">
    <div class="max-w-7xl mx-auto px-8 py-6 flex justify-between items-center">

      <NuxtLink to="/" class="group">
        <h1 class="font-serif text-2xl tracking-wide">
          The Student<span class="text-[#F7D6C4]">.</span>
        </h1>
        <p class="text-[9px] tracking-[4px] text-[#A6B1C2] uppercase mt-1">
          Academic Directory
        </p>
      </NuxtLink>

      <nav class="flex gap-8 text-sm tracking-wide">
        <NuxtLink to="/" class="hover:text-[#F7D6C4] transition-colors">
          Home
        </NuxtLink>
        <NuxtLink to="/about" class="hover:text-[#F7D6C4] transition-colors">
          About
        </NuxtLink>
      </nav>

    </div>
  </header>
</template>
