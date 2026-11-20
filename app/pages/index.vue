
<template>
  <div class="space-y-20">

    <!-- HERO -->
    <section class="relative py-16 md:py-24 border-b border-[#E7DFD7]">

      <div class="max-w-3xl">
        <p class="text-xs tracking-[5px] text-[#A68C7A] uppercase mb-6">
          Your Academic Community · 2026
        </p>

        <h1 class="font-serif text-5xl md:text-7xl
                   leading-tight text-[#1E253C]">
          Every Student
          <span class="italic text-[#A68C7A]">Has a Story.</span>
        </h1>

        <p class="text-[#506183] leading-8 mt-7 max-w-xl">
          Discover our student community through a collection
          of academic profiles, achievements, and experiences.
        </p>

        <div class="flex gap-4 mt-9">
          <a href="#directory">
            <AppButton
              label="Explore Directory"
              color="bg-[#1E253C] text-white"
            />
          </a>

          <NuxtLink to="/about">
            <AppButton
              label="About Us"
              color="bg-[#F7D6C4] text-[#1E253C]"
            />
          </NuxtLink>
        </div>
      </div>

      <div class="hidden md:block absolute right-8 bottom-12
                  text-right">
        <p class="font-serif italic text-6xl text-[#E7D8CC]">
          01—03
        </p>
        <p class="text-[10px] tracking-[3px] text-[#A6B1C2]">
          STUDENT COLLECTION
        </p>
      </div>

    </section>

    <!-- DIRECTORY -->
    <section id="directory">

      <div class="flex flex-col md:flex-row
                  md:justify-between md:items-end mb-9 gap-4">

        <div>
          <p class="text-xs tracking-[4px] text-[#A68C7A] mb-3">
            MEET THE COMMUNITY
          </p>

          <h2 class="font-serif text-4xl text-[#1E253C]">
            Student Directory
          </h2>
        </div>

        <p class="text-sm text-[#506183]">
          A closer look at our students · 03 Profiles
        </p>

      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2
                  lg:grid-cols-3 gap-7">

        <StudentCard
          name="Khizziah Legada"
          course="BS Information Technology"
          year="3rd Year"
          number="01"
          initials="KL"
        />

        <StudentCard
          name="Jane Doe"
          course="BS Computer Science"
          year="2nd Year"
          number="02"
          initials="JD"
        />

        <StudentCard
          name="John Smith"
          course="BS Data Science"
          year="1st Year"
          number="03"
          initials="JS"
        />

      </div>
    </section>

    <!-- FEATURE BANNER -->
    <section class="bg-[#1E253C] rounded-xl p-9 md:p-14
                    relative overflow-hidden">

      <div class="absolute -right-10 -bottom-24
                  text-[230px] font-serif text-white/5">
        S
      </div>

      <div class="relative z-10 max-w-2xl">
        <p class="text-xs tracking-[4px] text-[#F7D6C4] mb-5">
          BEYOND THE CLASSROOM
        </p>

        <h2 class="font-serif text-3xl md:text-4xl
                   text-[#FCF8F2] leading-snug">
          Learning is a journey,
          not just a destination.
        </h2>

        <p class="text-sm leading-7 text-[#A6B1C2] mt-5 max-w-lg">
          Celebrate academic growth, build meaningful
          connections, and make every learning experience count.
        </p>

        <NuxtLink to="/about" class="inline-block mt-8">
          <AppButton
            label="Discover Our Portal"
            color="bg-[#F7D6C4] text-[#1E253C]"
          />
        </NuxtLink>
      </div>

    </section>

    <!-- INFORMATION -->
    <section class="pb-8">

      <div class="mb-8">
        <p class="text-xs tracking-[4px] text-[#A68C7A] mb-3">
          WHAT WE VALUE
        </p>

        <h2 class="font-serif text-4xl text-[#1E253C]">
          More Than Academics
        </h2>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">

        <InfoCard
          title="Academic Excellence"
          description="Our students are encouraged to develop their knowledge, strengthen their skills, and pursue excellence in their chosen fields."
        />

        <InfoCard
          title="Campus Life"
          description="From student organizations to creative activities, campus life creates opportunities for growth, collaboration, and lasting memories."
        />

      </div>
    </section>

  </div>
</template>
