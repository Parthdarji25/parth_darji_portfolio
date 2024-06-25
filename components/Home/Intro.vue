<template>
  <!-- Home Page Intro - 1 -->
  <div class="space-y-6">
    <NuxtImg
      src="/profile.jpg"
      alt="Parth"
      class="ring-2 border ring-gray-200 border-gray-300 dark:ring-white/10 dark:border-gray-800 hover:ring-4 transition-all duration-300 bg-gray-200 dark:bg-gray-900 rounded-full h-12 w-12 sm:h-16 sm:w-16"
      sizes="48px sm:64px"
      placeholder
      format="webp"
    />
    <h1
      class="text-xl font-bold tracking-tight text-gray-800 dark:text-gray-100"
    >
      Hello!
    </h1>
    <p class="text-gray-900 dark:text-gray-400">
      I'm Parth Darji, I work as a Software Engineer and with background in
      B.Sc. IT (Graduated from SVKM's UPG College). I specialize in building Full Stack
      applications and sites using Javascript, React, Vue &amp; Node.Currently
      Working as a Software engineer in
      <a href="https://in.webuy.com/" target="_blank"
        class=" hover:text-red-600 font-bold">CeX Webuy Entertainment Private Limited.</a
      >
    </p>
    <p class="text-gray-900 dark:text-gray-400">
      I'm passionate in learning new technologies, building responsive websites,
      and documenting my working process when it comes to complicated feature.
    </p>
  </div>
</template>

<script setup>
useSeoMeta({
  title: "Parth Darji",
  description:
    "I'm Parth, your friendly neighborhood software, engineer and designer from Mumbai, India. I specialize in building web applications and sites using Javascript, React, Vue & Node.",
});
</script>
