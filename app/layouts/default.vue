<template>
  <div class="min-h-screen bg-[#FCF8F2] flex flex-col font-sans">
    <AppHeader />
    <main class="flex-grow container mx-auto p-8 max-w-5xl">
      <slot />
    </main>
    <AppFooter />
  </div>
</template>