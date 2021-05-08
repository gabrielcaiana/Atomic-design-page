<template>
  <div class="app">
   <Header />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { Header } from '@/components/organisms';

export default defineComponent({
  name: 'App',
  components: {
    Header,
  },
});
</script>

<style lang="scss" scoped>
  .app {
    padding: 2rem;
  }
</style>
