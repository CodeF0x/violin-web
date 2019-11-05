<template>
  <div class="progress-con">
    <div id="timer-start">0:00</div>
    <progress id="progress-value" value="0" max="100"></progress>
    <div id="timer-end">0:00</div>
  </div>
</template>

<script>
export default {
  name: 'ProgressCon'
}
</script>


<style scoped>
.progress-con {
  grid-row: 2;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}
</style>