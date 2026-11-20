
<template>
  <header class="fixed top-0 left-0 z-50 w-full border-b border-[#1E253C]/10 bg-[#FCF8F2]/90 backdrop-blur-md">
    <nav class="mx-auto flex h-[76px] max-w-[1500px] items-center justify-between px-6 md:px-12 lg:px-20">
      <NuxtLink to="/" class="text-lg font-semibold tracking-[0.18em] text-[#1E253C]">
        KL<span class="text-[#A6B1C2]">.</span>
      </NuxtLink>

      <div class="flex items-center gap-8 text-sm tracking-wide">
        <NuxtLink
          to="/"
          exact-active-class="!text-[#1E253C] after:scale-x-100"
          class="relative py-2 text-[#506183] transition-colors duration-300 hover:text-[#1E253C] after:absolute after:bottom-0 after:left-0 after:h-[1px] after:w-full after:origin-left after:scale-x-0 after:bg-[#1E253C] after:transition-transform after:duration-300 hover:after:scale-x-100"
        >
          Home
        </NuxtLink>

        <NuxtLink
          to="/profile"
          active-class="!text-[#1E253C] after:scale-x-100"
          class="relative py-2 text-[#506183] transition-colors duration-300 hover:text-[#1E253C] after:absolute after:bottom-0 after:left-0 after:h-[1px] after:w-full after:origin-left after:scale-x-0 after:bg-[#1E253C] after:transition-transform after:duration-300 hover:after:scale-x-100"
        >
          Profile
        </NuxtLink>
      </div>
    </nav>
  </header>
</template>
