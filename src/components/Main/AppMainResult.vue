<template>
  <section class="body">
    result
    <ResultInput/>
    <ResultOutput/>
  </section>
</template>

<script setup lang="ts">
import ResultInput from './result/ResultInput.vue';
import ResultOutput from './result/ResultOutput.vue';

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.body {
  background: tomato;
  min-height: 100vh;
}
</style>
