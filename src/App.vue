<script>
import AppTitle from './components/AppTitle.vue';
import AppJumbo from './components/AppJumbo.vue';

export default {
    name: 'MyApp',
    components: {
      AppTitle,
      AppJumbo,
  }
}
</script>

<template>
  <AppTitle />
  <AppJumbo />
</template>
