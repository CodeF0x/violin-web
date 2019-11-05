<template>
  <div id="main-container">
    <TopBg></TopBg>
    <FileCon></FileCon>
    <Sort></Sort>
    <Songs></Songs>
    <AlbumImage></AlbumImage>
    <BottomBg></BottomBg>
  </div>
</template>

<script>
import BottomBg from './BottomBg'
import AlbumImage from './AlbumImage'
import Songs from './Songs'
import Sort from './Sort'
import FileCon from './FileCon'
import TopBg from './TopBg'

export default {
  name: 'MainContainer',
  components: {
    BottomBg,
    AlbumImage,
    Songs,
    Sort,
    FileCon,
    TopBg
  }
};
</script>

<style>
#main-container {
  display: grid;
  grid-template-rows: 10vh 5vh auto 130px;
  grid-template-columns: 130px 1fr 1fr 1fr;
  background-color: var(--bg-color);
  height: 100vh;
}
</style>