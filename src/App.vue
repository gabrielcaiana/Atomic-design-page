<template>
  <div class="app">
    <Container>
      <Header />
      <Presentation />
      <Services />
    </Container>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { Container } from '@/components/bosons';
import { Header, Presentation, Services } from '@/components/organisms';

export default defineComponent({
  name: 'App',
  components: {
    Container,
    Header,
    Presentation,
    Services,
  },
});
</script>

<style lang="scss" scoped>
.app {
  padding: 2rem;
}
</style>
