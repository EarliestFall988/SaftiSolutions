<template>
  <li>
    <div class="flex flex-start items-center pt-3">
      <div class="bg-green-300 w-2 h-2 rounded-full -ml-1 mr-3"></div>
      <p class="text-gray-400 text-sm">{{date}}</p>
    </div>
    <div class="mt-0.5 ml-4 mb-6">
      <h4 class="text-gray-50 font-semibold text-xl mb-1.5">
        {{title}}
      </h4>
      <p class="text-gray-300 mb-3">
        {{description}}
      </p>
    </div>
  </li>
</template>

<script>
export default {
  name: 'TimeLineComponent',
  props: {
    date: {
      type: String,
      default: '',
    },
    title: {
      type: String,
      default: '',
    },
    description: {
      type: String,
      default: '',
    },
  },
}
</script>
