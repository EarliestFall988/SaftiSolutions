<template>
  <div class="flex-1 justify-evenly mx-5 rounded-sm p-3 my-5 bg-gray-700">
    <div class="flex flex-row">
      <span :class=icon></span>
      <div v-if="title !== ''" class="flex-1">
        <h2 class="text-white font-semibold font-sans text-2x1 mb-2">
          {{ title }}
        </h2>
      </div>
    </div>
    <p class="text-gray-300 p-5">{{ message }}</p>
  </div>
</template>

<script>
export default {
  name: 'NoticeCard',
  props: {
    title: {
      type: String,
      default: '',
    },
    message: {
      type: String,
      default: '',
    },
    icon : {
      type: String,
      default: '',
    }
  },
}
</script>
