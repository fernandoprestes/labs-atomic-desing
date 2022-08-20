<script lang="ts" setup>
  import { SocialNetworks } from '~/components/molecules';
</script>

<template>
  <div class="presentation">
    <SocialNetworks />
    <img
      class="presentation"
      src="/presentation.svg"
      alt="Apresentação"
    />
  </div>
</template>
<style lang="scss" scoped>
  .presentation {
    position: relative;
    display: grid;
    justify-content: center;

    .presentation {
      justify-self: center;
      width: 80%;
    }

    .social-networks {
      position: absolute;
      top: 50%;
      left: 0;
      transform: translateY(-50%);
    }
  }
</style>
