<template>
  <ul class="flex flex-col gap-y-1">
    <TagListItem v-for="tag in tags" :key="tag.id">{{ tag.name }}</TagListItem>
  </ul>
</template>

<script lang="ts" setup>
const { tags } = useTagsStore()
</script>

<style></style>
