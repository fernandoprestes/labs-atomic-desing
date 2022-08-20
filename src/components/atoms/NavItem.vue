<script lang="ts" setup>
  interface Props {
    text: string;
    to: string;
  }
  defineProps<Props>();
</script>
<template>
  <router-link
    class="nav-item"
    :to="to"
  >
    {{ text }}
  </router-link>
</template>

<style lang="scss" scoped>
  .nav-item {
    font-size: 1.3rem;
    color: #293947;
    text-decoration: none;
  }
</style>
