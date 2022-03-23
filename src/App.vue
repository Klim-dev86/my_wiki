<template>
    <AppHeader/>
    <AppMain/>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/Main/AppMain.vue';

@Options({
  components: {
    AppHeader,
    AppMain,
  },
})
export default class App extends Vue {}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  width: 1400px;
  max-width: 100%;
  margin: auto;
}

</style>
