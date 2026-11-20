
<template>
  <div class="min-h-screen bg-[#FCF8F2] flex flex-col font-sans">

    <AppHeader />

    <main class="flex-grow w-full max-w-7xl mx-auto px-6 md:px-10 py-10">
      <slot />
    </main>

    <AppFooter />

  </div>
</template>
