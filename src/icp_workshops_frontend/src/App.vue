<template>
  <div class="container mx-auto flex flex-col items-center justify-center">
    <Icp />
    <Calculator />
  </div>
</template>

<script>
import Icp from './components/Icp.vue';
import Calculator from './components/Calculator.vue';

export default {
  name: 'App',
  components: {
    Icp,
    Calculator,
  },
}
</script>