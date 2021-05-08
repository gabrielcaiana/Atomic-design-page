<template>
  <div class="app">
   <Header />
   <Presentation />
   <Services />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { Header, Presentation, Services } from '@/components/organisms';

export default defineComponent({
  name: 'App',
  components: {
    Header,
    Presentation,
    Services
  },
});
</script>

<style lang="scss" scoped>
  .app {
    padding: 2rem;
  }
</style>
