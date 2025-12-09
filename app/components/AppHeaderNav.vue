<template>
  <nav class="hidden grow sm:block">
    <ul class="flex items-center gap-x-8">
      <li class="mr-auto">
        <AppHeaderNavLink to="/playlists">Library</AppHeaderNavLink>
      </li>
      <li>
        <AppHeaderNavLink to="/login">Log In</AppHeaderNavLink>
      </li>
      <AppButton to="/register">Sign Up</AppButton>
    </ul>
  </nav>
</template>

<script lang="ts" setup></script>

<style></style>
