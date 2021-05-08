<template>
  <div class="services">
    <Service
      title="Front end"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat aliquam eligendi velit libero assumenda. Velit aliquam laboriosam esse modi repellat, sit ipsum laudantium porro repudiandae sed cumque architecto inventore! Deserunt!"
    />

    <Service
      title="Back end"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat aliquam eligendi velit libero assumenda. Velit aliquam laboriosam esse modi repellat, sit ipsum laudantium porro repudiandae sed cumque architecto inventore! Deserunt!"
    />

    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat aliquam eligendi velit libero assumenda. Velit aliquam laboriosam esse modi repellat, sit ipsum laudantium porro repudiandae sed cumque architecto inventore! Deserunt!"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { Service } from '@/components/molecules';

export default defineComponent({
  components: {
    Service,
  },
});
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
