<template>
  <div>
    <div class="control-con">
      <div id="shuffle"></div>
      <div id="last-song"></div>
      <div id="play"></div>
      <div id="next-song"></div>
      <div id="repeat"></div>
    </div>
    <div class="progress-con">
      <div id="timer-start">0:00</div>
      <progress id="progress-value" value="0" max="100"></progress>
      <div id="timer-end">0:00</div>
    </div>
    <div class="song-info">
      <div id="song-title">Something</div>
      <div>&nbsp;by&nbsp;</div>
      <div id="song-artist">Someone</div>
      <div id="volume-wrapper">
        <div id="volume-button"></div>
        <input type="range" min="0" max="100" value="100" id="volume" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BottomBg"
};
</script>