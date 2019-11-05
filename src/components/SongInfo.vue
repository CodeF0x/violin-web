<template>
  <div class="song-info">
    <div id="song-title">Something</div>
    <div>&nbsp;by&nbsp;</div>
    <div id="song-artist">Someone</div>
    <div id="volume-wrapper">
      <div id="volume-button"></div>
      <input type="range" min="0" max="100" value="100" id="volume" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'SongInfo'
}
</script>

<style scoped>
.song-info {
  display: flex;
  justify-content: center;
  align-items: center;
  color: var(--text-color);
  font-size: 0.9em;
}
</style>