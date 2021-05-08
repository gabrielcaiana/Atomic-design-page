<template>
  <div class="social-networks">
    <SocialLink
      name="github"
      to="http://github.com/gabrielcaiana"
      icon="github.svg"
    />
    <SocialLink
      name="twitter"
      to="http://twitter.com"
      icon="twitter.svg"
    />
    <SocialLink
      name="facebook"
      to="http://facebook.com"
      icon="facebook.svg"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { SocialLink } from '@/components/atoms';

export default defineComponent({
  components: {
    SocialLink
  },
});
</script>

<style lang="scss" scoped>
.social-networks {
  display: grid;
  grid-gap: 1rem;
}
</style>
