<template>
  <div>
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