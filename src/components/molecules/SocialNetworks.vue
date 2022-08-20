<script lang="ts" setup>
  import { SocialLink } from '../atoms';
</script>

<template>
  <div class="social-networks">
    <SocialLink
      to="/"
      name="facebook"
      icon="/icons/facebook.svg"
    />
    <SocialLink
      to="/"
      name="facebook"
      icon="/icons/github.svg"
    />
    <SocialLink
      to="/"
      name="facebook"
      icon="/icons/twitter.svg"
    />
  </div>
</template>
<style lang="scss" scoped>
  .social-networks {
    display: grid;
    grid-gap: 1rem;
  }
</style>
