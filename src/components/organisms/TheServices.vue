<script lang="ts" setup>
  import { Service } from '~/components/molecules';
</script>

<template>
  <div class="services">
    <Service
      title="Front end"
      description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptates tempore quia adipisci rem ea. Cum labore est vitae repellendus voluptatum quidem tenetur tempore, quia aliquam quos, amet quisquam. Asperiores, perspiciatis!"
    />
    <Service
      title="Back end"
      description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptates tempore quia adipisci rem ea. Cum labore est vitae repellendus voluptatum quidem tenetur tempore, quia aliquam quos, amet quisquam. Asperiores, perspiciatis!"
    />
    <Service
      title="Manutenção"
      description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptates tempore quia adipisci rem ea. Cum labore est vitae repellendus voluptatum quidem tenetur tempore, quia aliquam quos, amet quisquam. Asperiores, perspiciatis!"
    />
  </div>
</template>
<style lang="scss" scoped>
  .services {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 5rem;
  }
</style>
