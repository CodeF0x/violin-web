<template>
  <div>
    <div id="by-name">Name</div>
    <div id="by-album">Album</div>
    <div id="by-artist">Artist</div>
  </div>
</template>

<script>
export default {
  name: 'Sort'
}
</script>

<style>
#by-name,
#by-album,
#by-artist {
  margin-top: 10px;
  grid-row: 2;
  justify-self: center;
  display: none; /** Issue #144 */
}

#by-name:hover,
#by-album:hover,
#by-artist:hover {
  cursor: pointer;
}
</style>