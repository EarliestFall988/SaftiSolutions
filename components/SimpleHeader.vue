<template>
  <div class="my-4 flex flex-row">
    <div class="flex-0 w-7 text-3xl bg-blue-500 rounded rounded-l-none">

    </div>
    <h1 class="flex-1 mx-5 text-white font-bold text-align-center">{{name}}</h1>
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
