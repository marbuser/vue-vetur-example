<template>
  <div id="app">
    <test-component></test-component>
  </div>
</template>

<script>
import testComponent from '@/components/TestComponent.vue';

export default {
  name: 'app',
  components: {
    testComponent,
  },
};
</script>
