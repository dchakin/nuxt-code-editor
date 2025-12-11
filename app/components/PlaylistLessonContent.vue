<template>
  <article
    class="prose max-w-none prose-h3:m-0 prose-h3:dark:text-gray-200 prose-p:mt-2 prose-p:dark:text-gray-300"
  >
    <header>
      <h3>{{ title }}</h3>
    </header>
    <p>
      {{ description }}
    </p>
  </article>
</template>

<script lang="ts" setup>
defineProps<{
  title: string
  description: string
}>()
</script>

<style></style>
