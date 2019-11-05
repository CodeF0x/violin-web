<template>
  <div class="bottom-bg">
    <ControlCon></ControlCon>
    <ProgressCon></ProgressCon>
    <SongInfo></SongInfo>
  </div>
</template>

<script>
import ControlCon from './ControlCon'
import ProgressCon from './ProgressCon'
import SongInfo from './SongInfo'

export default {
  name: 'BottomBg',
  components: {
    ControlCon,
    ProgressCon,
    SongInfo
  }
}
</script>

<style scoped>
.bottom-bg {
  grid-row: 4;
  grid-column: 2/5;
  background-color: var(--con-color);
  display: grid;
  grid-template-rows: 1fr 1fr 1fr;
}
</style>