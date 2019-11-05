<template>
  <div class="control-con">
    <div id="shuffle"></div>
    <div id="last-song"></div>
    <div id="play"></div>
    <div id="next-song"></div>
    <div id="repeat"></div>
  </div>
</template>

<script>
export default {
  name: 'ControlCon'
}
</script>

<style scoped>
.control-con {
  grid-row: 1;
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  align-content: flex-end;
}

#shuffle,
#last-song,
#play,
#next-song,
#repeat {
  -webkit-app-region: no-drag;
  height: 25px;
  width: 25px;
  cursor: pointer;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  justify-self: center;
  align-self: center;
}

#shuffle {
  grid-column: 1;
  background-image: url('/assets/shuffle.png');
}

#last-song {
  grid-column: 2;
  background-image: url('/assets/backward.png');
}

#play {
  grid-column: 3;
  background-image: url('/assets/play.png');
}

#next-song {
  grid-column: 4;
  background-image: url('/assets/forward.png');
}

#repeat {
  grid-column: 5;
  background-image: url('/assets/repeat.png');
}

#next-song:hover,
#last-song:hover,
#shuffle:hover,
#play:hover,
#repeat:hover {
  transform: scale(1.1);
  transition: 0.3s ease-in-out;
}
</style>

