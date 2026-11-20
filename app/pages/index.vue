<template>
  <div class="space-y-12">
    <div>
      <h1 class="text-4xl font-serif font-bold text-[#1E253C] mb-2">Student Directory</h1>
      <p class="text-[#506183]">Demonstrating reusable components and props.</p>
    </div>

    <!-- 3 Student Cards -->
    <section class="grid grid-cols-1 md:grid-cols-3 gap-6">
      <StudentCard name="Khizziah Legada" course="BS Information Technology" year="3rd Year" />
      <StudentCard name="Jane Doe" course="BS Computer Science" year="2nd Year" />
      <StudentCard name="John Smith" course="BS Data Science" year="1st Year" />
    </section>

    <!-- Buttons -->
    <section class="flex gap-4 pt-8">
      <AppButton label="View Transcript" color="bg-[#506183] text-white" />
      <AppButton label="Edit Profile" color="bg-[#F7D6C4] text-[#1E253C]" />
    </section>

    <!-- Info Cards -->
    <section class="grid grid-cols-1 md:grid-cols-2 gap-6 pt-8">
      <InfoCard title="Academic Excellence" description="Our students consistently achieve high honors in their respective fields of study." />
      <InfoCard title="Campus Life" description="Join various organizations, esports teams, and art clubs to enrich your student experience." />
    </section>
  </div>
</template>