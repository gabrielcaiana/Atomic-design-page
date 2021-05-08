<template>
  <div class="app">
   <Header />
   <Presentation />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { Header, Presentation } from '@/components/organisms';

export default defineComponent({
  name: 'App',
  components: {
    Header,
    Presentation
  },
});
</script>

<style lang="scss" scoped>
  .app {
    padding: 2rem;
  }
</style>
