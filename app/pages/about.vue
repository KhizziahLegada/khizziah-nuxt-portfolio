
<template>
  <div class="max-w-4xl mx-auto py-16">

    <p class="text-xs tracking-[5px] text-[#A68C7A] mb-6">
      OUR STORY · STUDENT PORTAL
    </p>

    <h1 class="font-serif text-5xl md:text-7xl
               text-[#1E253C] leading-tight mb-10">
      A Place for
      <span class="italic text-[#A68C7A]">Every Student.</span>
    </h1>

    <div class="border-l-2 border-[#F7D6C4] pl-7 mb-14">
      <p class="text-lg text-[#506183] leading-9">
        The Student Information Portal is a simple and
        organized platform created to present student
        profiles and academic information in one place.
      </p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 mb-14">

      <div class="bg-white p-8 rounded-xl border border-[#E7DFD7]">
        <p class="text-xs tracking-[3px] text-[#A68C7A] mb-5">
          01 — OUR PURPOSE
        </p>

        <h2 class="font-serif text-2xl text-[#1E253C] mb-4">
          Organized Information
        </h2>

        <p class="text-sm text-[#506183] leading-7">
          Providing an accessible way to view and organize
          student profiles and their academic details.
        </p>
      </div>

      <div class="bg-white p-8 rounded-xl border border-[#E7DFD7]">
        <p class="text-xs tracking-[3px] text-[#A68C7A] mb-5">
          02 — OUR APPROACH
        </p>

        <h2 class="font-serif text-2xl text-[#1E253C] mb-4">
          Reusable Components
        </h2>

        <p class="text-sm text-[#506183] leading-7">
          Using Vue and Nuxt components to create consistent
          layouts and demonstrate the use of props.
        </p>
      </div>

    </div>

    <NuxtLink to="/">
      <AppButton
        label="Return to Student Directory"
        color="bg-[#1E253C] text-white"
      />
    </NuxtLink>

  </div>
</template>
