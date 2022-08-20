<script lang="ts" setup>
  interface Props {
    title: string;
    description: string;
  }
  defineProps<Props>();
</script>

<template>
  <div class="service">
    <h2 class="title">{{ title }}</h2>
    <p class="description">{{ description }}</p>
  </div>
</template>
<style lang="scss" scoped>
  .service {
    .title {
      margin-bottom: 0.8rem;
      font-weight: bold;
      color: #935e92;
    }

    .description {
      line-height: 1.5;
      color: #293947;
    }
  }
</style>
