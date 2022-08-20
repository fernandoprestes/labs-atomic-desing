<script lang="ts" setup>
  import { NavItem } from '../atoms';
</script>
<template>
  <nav class="nav-bar">
    <NavItem
      text="Home"
      to="/"
    />
    <NavItem
      text="Serviços"
      to="/service"
    />
    <NavItem
      text="Sobre"
      to="/about"
    />
    <NavItem
      text="Contato"
      to="/contact"
    />
  </nav>
</template>
<style lang="scss" scoped>
  .nav-bar {
    display: grid;
    grid-auto-flow: column;
    grid-gap: 2.5rem;
    width: max-content;
  }
</style>
