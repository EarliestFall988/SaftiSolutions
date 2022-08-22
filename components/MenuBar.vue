<template>
  <div class="my-2 ml-5 mr-3 flex flex-row-reverse">


    <div class="flex-1 justify-end py-2 mr-5 flex flex-row">

      <nuxt-link
        to="/"
        class="
          text-white
          px-3
          py-1
          bg-transparent
          hover:bg-gray-800
          rounded
          ml-5
          uppercase
        "
        >Home</nuxt-link
      >
      <nuxt-link
        to="DownloadPage"
        class="
          text-white
          py-1
          px-3
          bg-transparent
          hover:bg-gray-800
          rounded
          mx-5
          uppercase
        "
        >Install</nuxt-link
      >
      <nuxt-link
        to="DownloadPage"
        class="
          text-white
          py-1
          px-3
          bg-transparent
          hover:bg-gray-800
          rounded
          mx-3
          uppercase
        "
        >About</nuxt-link
      >
      <nuxt-link
        to="LogInPage"
        class="px-3 py-1 text-white bg-gray-900 hover:bg-blue-600 rounded rl-5 uppercase"
        >Login</nuxt-link
      >
    </div>
    <a href="/">
      <icon-component
        icon="logo"
        class="flex-2 w-30 h-12 pt-2 pl-2"
      ></icon-component>
    </a>
  </div>
</template>

<script>
export default {
  name: 'MenuBar',
}
</script>




