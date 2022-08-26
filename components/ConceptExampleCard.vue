<template>
  <div class="flex flex-row mx-5 rounded-sm bg-slate-700 my-2">
    <div class="flex-1 py-4 ml-5 pr-5 my-1 items-start border-r-2 border-slate-600">
      <p class="text-white font-medium text-lg">{{ title }}</p>
      <p class="text-gray-300 mt-2 ml-2">{{ description }}</p>
    </div>
    <div class="flex-1 py-4 mx-5 my-1 items-start ">
      <p class="text-white font-medium text-lg">{{ exampleTitle }}</p>
      <p class="text-gray-300 mt-2 ml-2">{{ exampleDescription }}</p>
    </div>
  </div>
</template>


<script>
export default {
  name: "ConceptExampleCard",
  props: {
    title: {
      type: String,
      default: ''
    },
    description:{
      type: String,
      default: ''
    },
    exampleTitle:{
     type: String,
      default: ''
    },
    exampleDescription:{
      type: String,
      default: ''
    }
  }
}
</script>
