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

<style>
.song-info {
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 0.9em;
  grid-row: 3;
}

#song-title,
#song-artist {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

#volume-wrapper {
  position: absolute;
  right: 10px;
}

#volume-button {
  float: left;
  height: 20px;
  width: 20px;
  background-image: url('../../assets/volume.png');
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}

input[type='range'] {
  margin: 0;
  padding: 0;
  padding-left: 10px;
}
</style>