<template>
  <NuxtLink to="/" class="flex items-center gap-x-1 font-black sm:gap-x-2">
    <Icon name="code" :class="`-rotate-6 ${iconClasses}`" />

    <span v-if="$slots.default">
      <slot />
    </span>
  </NuxtLink>
</template>

<script lang="ts" setup>
defineProps<{ iconClasses: string }>()
</script>

<style></style>
