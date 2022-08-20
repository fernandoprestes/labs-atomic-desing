<script lang="ts" setup>
  import { Logo } from '~/components/atoms';
  import { SearchForm, NavBar } from '~/components/molecules';
</script>

<template>
  <header class="header">
    <Logo />
    <NavBar />
    <SearchForm />
  </header>
</template>
<style lang="scss" scoped>
  .header {
    display: grid;
    grid-template-columns: 160px repeat(2, auto);
    align-items: center;
    justify-content: space-between;
    width: 100%;
  }
</style>
