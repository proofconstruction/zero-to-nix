<template>
  <div
    class="rounded border-1.5 border-light-gray bg-pale p-4 transition-colors duration-150 dark:border-gray dark:bg-dark-gray md:p-6 lg:p-8"
  >
    <div class="items-center justify-between space-y-4 md:flex md:space-y-0">
      <h1 class="text-lg font-light leading-snug md:text-xl lg:text-2xl">
        Stay up to date with what we're up to at
        <span class="font-semibold">Determinate Systems</span>
      </h1>

      <button
        @click="openModal"
        class="rounded bg-primary py-1.5 px-3 text-xs font-bold text-white transition-colors duration-150 hover:bg-light-gray hover:text-dark md:py-2 md:px-4 md:text-sm lg:text-base"
      >
        Subscribe
      </button>
    </div>
  </div>
</template>

<script setup lang="ts">
import { openModal } from "~/logic/state";
</script>
