<template>
  <div id="album-img"></div>
</template>

<script>
export default {
  name: 'AlbumImage'
}
</script>

<style scoped>
#album-img {
  grid-column: 1;
  grid-row: 4;
  background-color: gray;
  background-position: center;
  background-size: cover;
}
</style>