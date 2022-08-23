<template>
  <div class="flex-1 justify-evenly mx-5 rounded-lg px-2 pt-1 my-5">
    <box-icon name="rocket"></box-icon>
    <div v-if="title !== ''">
    <p class="text-white font-semibold font-sans text-2x1 mb-2">{{title}}</p>
    </div>
    <p class="text-gray-50 mb-5 ml-3">{{ message }}</p>
  </div>
</template>

<script>
export default {
  name: 'NoticeCard',
  props: {
    title: {
      type: String,
      default: ''
    },
    message: {
      type: String,
      default: ''
    },
  },
}
</script>
