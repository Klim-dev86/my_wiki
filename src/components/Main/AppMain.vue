<template>
  <main class="main">
    <AppMainList class="main__list"/>
    <AppMainResult class="main__result"/>
  </main>
</template>

<script setup lang="ts">
import AppMainList from './AppMainList.vue';
import AppMainResult from './AppMainResult.vue';

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.main {
  background: tomato;
  min-height: 100vh;
  display: grid;
  grid-template-columns: 30% 1fr;
}
</style>
