<template>
  <div class="flex flex-col gap-y-1">
    <AppLabel v-if="$slots.default" :for="id">
      <slot />
    </AppLabel>
    <AppInput :id="id" v-bind="$attrs" />
  </div>
</template>

<script lang="ts" setup>
defineOptions({
  inheritAttrs: false,
})

defineProps<{
  type: string
  id: string
}>()
</script>

<style></style>
