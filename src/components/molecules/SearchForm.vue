<script lang="ts" setup></script>

<template>
  <form class="search-form">
    <input
      type="search"
      placeholder="Buscar"
    />
    <button type="submit">
      <img
        src="/icons/search.svg"
        alt="search"
      />
    </button>
  </form>
</template>
<style lang="scss" scoped>
  .search-form {
    position: relative;
    width: max-content;

    input {
      padding: 0.5rem 1rem;
      border: 0;
      border-radius: 1rem;
      box-shadow: 0 5px 5px rgba(#000, 0.08);
    }

    button {
      position: absolute;
      top: 50%;
      right: 3px;
      display: grid;
      align-items: center;
      justify-items: center;
      width: 30px;
      height: 30px;
      background: #ff895f;
      border: 0;
      border-radius: 5rem;
      transform: translateY(-50%);
    }
  }
</style>
