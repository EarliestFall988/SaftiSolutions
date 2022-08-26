<template>
  <div class="bg-gray-900 pt-1 h-screen">
    <MenuBar></MenuBar>
    <div class="download-box">
    </div>
  </div>
</template>

<script>
export default {
  name: 'DownloadPage',
}
</script>

<style>
.download-box {
  display: flex;
  margin: auto;
  width: 50%;
  height: 50;
}

.download {
  background: red;
}
</style>
