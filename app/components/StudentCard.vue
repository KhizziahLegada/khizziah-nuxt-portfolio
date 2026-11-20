
<script setup>
defineProps({
  name: String,
  course: String,
  year: String,
  number: String,
  initials: String
})
</script>

<template>
  <article class="group bg-white border border-[#E7DFD7]
                  rounded-xl overflow-hidden
                  hover:-translate-y-2 hover:shadow-xl
                  transition-all duration-300">

    <div class="bg-[#1E253C] p-6 relative overflow-hidden">
      <span class="absolute -right-3 -top-12 text-8xl
                   font-serif text-white/5">
        {{ number }}
      </span>

      <p class="text-[10px] tracking-[3px] text-[#F7D6C4] uppercase">
        Student Profile
      </p>

      <div class="mt-7 w-16 h-16 rounded-full
                  bg-[#F7D6C4] flex items-center justify-center
                  text-[#1E253C] font-serif text-xl">
        {{ initials }}
      </div>
    </div>

    <div class="p-6">
      <p class="text-xs tracking-[2px] text-[#A6B1C2] mb-2">
        {{ number }} / DIRECTORY
      </p>

      <h2 class="font-serif text-xl text-[#1E253C] mb-4">
        {{ name }}
      </h2>

      <div class="border-t border-[#EAE5DF] pt-4 space-y-3">
        <div>
          <p class="text-[10px] tracking-widest text-[#A6B1C2] uppercase">
            Course
          </p>
          <p class="text-sm text-[#506183] mt-1">
            {{ course }}
          </p>
        </div>

        <div>
          <p class="text-[10px] tracking-widest text-[#A6B1C2] uppercase">
            Academic Level
          </p>
          <p class="text-sm text-[#506183] mt-1">
            {{ year }}
          </p>
        </div>
      </div>
    </div>

  </article>
</template>
