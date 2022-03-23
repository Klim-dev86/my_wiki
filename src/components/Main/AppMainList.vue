<template>
  <aside class="list">
    list of items
    <MainListItem class="list__item"/>
    <MainListItem/>
  </aside>
</template>

<script setup lang="ts">
import MainListItem from './list-item/MainListItem.vue';

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.list {
  background: purple;
  min-height: 100vh;
  padding: 10px;

  &__item:not(:last-child){
    margin-bottom: 10px;
  }
}
</style>
