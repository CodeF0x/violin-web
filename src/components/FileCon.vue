<template>
  <div class="file-con">
    <div class="creator">
      with ❤️ by
      <a href="#" id="creator-link">CodeF0x</a>
    </div>
    <a href="#" id="open-folder" class="btn">OPEN FOLDER</a>
    <input type="text" placeholder="Search by name" class="search" id="search" disabled />
  </div>
</template>

<script>
export default {
  name: 'FileCon'
}
</script>

<style>
.btn,
.file-con {
  grid-row: 1;
  grid-column: 2/5;
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.creator {
  font-size: 0.7rem;
}

#creator-link {
  text-decoration: none;
  -webkit-app-region: no-drag;
}

#creator-link:hover {
  cursor: pointer;
  font-weight: 900;
  transition: 0.3s ease-in-out;
}

.btn {
  text-decoration: none;
  padding: 5px 10px;
  background-color: var(--btn-color);
  border-radius: 5px;
  color: var(--text-color);
  font-weight: 900;
  font-size: 0.8em;
  cursor: pointer;
  -webkit-app-region: no-drag;
}

.btn:hover {
  background-color: var(--btn-color-hover);
  color: var(--text-color-hover);
}
</style>