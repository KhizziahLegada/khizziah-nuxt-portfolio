
<template>
  <section class="relative min-h-[calc(100svh-76px)] overflow-hidden bg-[#FCF8F2]">
    <div class="mx-auto grid min-h-[calc(100svh-76px)] max-w-[1600px] grid-cols-1 items-center gap-8 px-6 py-12 md:px-12 lg:grid-cols-[0.9fr_1.1fr] lg:gap-12 lg:px-20 lg:py-10">

      <!-- TEXT -->
      <div class="relative z-10 flex flex-col justify-center lg:py-12">
        <p class="mb-6 text-xs font-medium uppercase tracking-[0.35em] text-[#506183]">
          Welcome to my personal space
        </p>

        <h1 class="text-[clamp(3.5rem,7vw,7rem)] font-light leading-[0.95] tracking-[-0.065em] text-[#1E253C]">
          Khizziah
          <span class="block font-normal">Legada.</span>
        </h1>

        <div class="my-8 h-px w-20 bg-[#A6B1C2]"></div>

        <p class="max-w-md text-lg leading-8 text-[#506183]">
          An Information Technology student with an interest in creativity,
          design, technology, and discovering new perspectives.
        </p>

        <p class="mt-5 max-w-md text-sm leading-7 text-[#506183]/80">
          This is a little introduction to who I am, what I enjoy, and the
          experiences that continue to shape me.
        </p>

        <div class="mt-10">
          <NuxtLink
            to="/profile"
            class="group inline-flex items-center gap-5 border-b border-[#1E253C] pb-3 text-sm font-medium tracking-wide text-[#1E253C]"
          >
            Get to know me
            <span class="transition-transform duration-300 group-hover:translate-x-2">→</span>
          </NuxtLink>
        </div>

        <p class="mt-16 text-[10px] uppercase tracking-[0.3em] text-[#A6B1C2]">
          Personal Profile · 2026
        </p>
      </div>

      <!-- LARGE PORTRAIT -->
      <div class="relative mx-auto h-[58vh] min-h-[390px] w-full max-w-[680px] lg:h-[calc(100svh-150px)] lg:max-h-[790px] lg:min-h-[560px]">
        <div class="absolute inset-0 translate-x-3 translate-y-3 border border-[#A6B1C2]"></div>

        <div class="relative h-full w-full overflow-hidden bg-[#E9E2D9]">
          <img
            src="/images/mypic.png"
            alt="Portrait of Khizziah Legada"
            class="h-full w-full object-cover object-center transition-transform duration-700 hover:scale-[1.025]"
          />
        </div>

        <p class="absolute -bottom-8 right-0 text-[10px] uppercase tracking-[0.25em] text-[#506183]">
          A little piece of me
        </p>
      </div>

    </div>
  </section>
</template>
