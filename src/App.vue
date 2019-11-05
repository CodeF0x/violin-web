<template>
  <div id="app">
    <MainContainer></MainContainer>
  </div>
</template>

<script>
import MainContainer from './components/MainContainer.vue';

export default {
  name: 'app',
  components: {
    MainContainer
  }
};
</script>

<style>
#app {
  display: grid;
  grid-template-rows: 10vh 5vh auto 130px;
  grid-template-columns: 130px 1fr 1fr 1fr;
  background-color: var(--bg-color);
  height: 100vh;
}
</style>
