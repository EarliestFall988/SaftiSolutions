<template>
  <div class="bg-gray-900 pt-1 h-screen">
    <MenuBar></MenuBar>
    <div class="download-box">
      <DownloadButton />
    </div>
  </div>
</template>

<script>
import DownloadButtonVue from '~/components/DownloadButton.vue'
import MenuBarVue from '~/components/MenuBar.vue'
export default {
  name: 'DownloadPage',
  components: [
    DownloadButtonVue,
    MenuBarVue,
  ]
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
