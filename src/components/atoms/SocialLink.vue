<script lang="ts" setup>
  interface Props {
    name: string;
    icon: string;
    to: string;
  }
  defineProps<Props>();
</script>

<template>
  <a
    class="social-link"
    target="_blank"
    :href="to"
  >
    <img
      :src="icon"
      :alt="name"
    />
  </a>
</template>

<style lang="scss" scoped>
  .social-link {
    display: grid;
    align-items: center;
    justify-items: center;
    width: 47px;
    height: 47px;
    background-color: #ff895f;
    border-radius: 5rem;
    transition: transform 0.2s linear;

    &:hover {
      transform: scale(1.1);
    }

    img {
      width: 23px;
      height: 23px;
    }
  }
</style>
