<template>
  <div class="space-y-6 text-center">
    <div class="flex justify-center">
      <NuxtImg src="/avatar.JPG" alt="Ankit Ranjan Sinha"
      class="items-center justify-center ring-2 border ring-gray-200 border-gray-300 dark:ring-white/10 dark:border-gray-800 hover:ring-4 transition-all duration-300 bg-gray-200 dark:bg-gray-900 rounded-full h-12 w-12 sm:h-16 sm:w-16"
      sizes="48px sm:64px" placeholder format="webp" />
    </div>
    <h1 class="text-xl font-bold tracking-tight text-gray-800 dark:text-gray-100">
      Hello!
    </h1>
    <p class="text-gray-900 dark:text-gray-400">
      I'm Ankit Ranjan, I work as a Senior Software Engineer, Product Engineer and Designer from
      Pune, India. I specialize in building web applications, node services, and sites
      using Javascript, Vue &amp; Node, with a focus on creating microservices. I've procrastinated building this
      website for years but finally it's here, I've carved out my own little
      nook on the internet to share my silly experiments, nifty projects, and
      thoughts (mostly about tech and design).
    </p>
    <p class="text-gray-900 dark:text-gray-400">
      By day, I'm a Fullstack Developer at
      <a href="https://genpact.com" target="_blank" class="underline">Genpact</a>, and
      by night (and weekends), I'm busy tinkering with some random tool or app
      that I am building.
    </p>
  </div>
</template>

<script setup>
useSeoMeta({
  title: "Ankit Ranjan Sinha",
  description:
    "I'm Ankit Ranjan, your friendly neighborhood software, product engineer and designer from Pune, India. I specialize in building web applications and sites using Javascript, React, Vue & Node.",
});
</script>
