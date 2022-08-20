<script lang="ts" setup>
  import { TheHeader, ThePresentation, TheServices } from '~/components/organisms';
</script>

<template>
  <main class="o-container home-template">
    <TheHeader />
    <ThePresentation />
    <TheServices />
  </main>
</template>
<style lang="scss" scoped>
  .home-template {
    display: grid;
    grid-gap: 5rem;
    padding: 32px 32px 0;
  }
</style>
