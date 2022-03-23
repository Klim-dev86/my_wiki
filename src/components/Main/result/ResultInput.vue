<template>
  <section class="input">
    input
  </section>
</template>

<script setup lang="ts">

const props = defineProps({
  content: String,
});

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.input {
  background: lemonchiffon;
  padding: 20px;
}
</style>
