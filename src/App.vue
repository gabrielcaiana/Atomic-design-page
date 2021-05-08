<template>
<div class="app">
  <NavBar />
  <SearchForm />
</div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { NavBar, SearchForm } from '@/components/molecules'

export default defineComponent({
  name: "App",
  components: {
    NavBar,
    SearchForm
  }
});
</script>

<style lang="scss" scoped>
  .app {
    width: 150px;
  }
</style>