<template>
 <HomePage />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { HomePage } from '@/components/pages'


export default defineComponent({
  name: 'App',
  components: {
    HomePage
  },
});
</script>

