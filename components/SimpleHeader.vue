<template>
  <div class="my-4 flex flex-row py-5">
    <div class="flex-0 w-2 bg-blue-500 rounded rounded-l-none">

    </div>
    <h1 class="flex-1 mx-5  text-white font-bold text-align-center text-2xl">{{name}}</h1>
  </div>
</template>

<script>
export default {
  name: 'SimpleHeader',
  props : {
    name : {
      type : String,
      default : ''
    }
  }
}
</script>
