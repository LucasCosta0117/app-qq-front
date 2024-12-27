<template>
  <PropagandaCarousel />
  <HelloWorld />
</template>

<script>
import { defineComponent } from 'vue';

// Components
import HelloWorld from '../components/HelloWorld';
import PropagandaCarousel from '../components/PropagandaCarousel';

export default defineComponent({
  name: 'HomeView',

  components: {
    HelloWorld,
    PropagandaCarousel
  },
});
</script>
