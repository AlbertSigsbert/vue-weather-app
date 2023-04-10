<template>
  <header class="sticky top-0 shadow-lg">
    <nav
      class="mx-[6%] flex flex-col items-center gap-4 py-6 md:flex-row md:justify-between"
    >
      <router-link :to="{ name: 'Home' }">
        <div class="flex items-center gap-3">
          <SunIcon class="h-6 w-6 text-blue-500" />
          <p class="text-2xl">VueWeather</p>
        </div>
      </router-link>
      <div class="flex gap-3">
        <InformationCircleIcon
          class="h-6 w-6 text-blue-500 hover:text-blue-400 duration-150 cursor-pointer"
        />
        <PlusIcon
          class="h-6 w-6 text-blue-800 hover:text-blue-700 duration-150 cursor-pointer"
        />
      </div>
    </nav>
  </header>
</template>

<script setup>
import {
  SunIcon,
  InformationCircleIcon,
  PlusIcon,
} from "@heroicons/vue/24/solid";
</script>
