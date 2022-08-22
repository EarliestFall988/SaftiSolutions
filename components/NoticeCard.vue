<template>
  <div class=" flex-1 bg-gray-700 rounded-lg mx-2 px-2 pt-1">
    <div v-if="title !== ''">
    <p class="text-white font-medium font-sans text-2x1">{{title}}</p>
    <br>
    </div>
    <p class="text-gray-50 pb-1">{{ message }}</p>
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
