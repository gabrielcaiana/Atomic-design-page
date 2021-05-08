<template>
<div class="app">
  <SocialNetworks />
</div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { SocialNetworks } from '@/components/molecules'

export default defineComponent({
  name: "App",
  components: {
    SocialNetworks
  }
});
</script>

<style lang="scss" scoped>
  .app {
    width: 150px;
  }
</style>