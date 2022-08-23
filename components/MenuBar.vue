<template>
  <div class="flex flex-col md:flex-row mx-3">
    <a href="/">
      <icon-component
        icon="logo"
        class="flex-2 w-40 h-10 my-5 mx-auto justify-evenly"
      ></icon-component>
    </a>

    <div
      class="
        flex-1
        items-center
        lg:justify-end
        sm:justify-center
        md:py-2
        md:mr-5
        flex
        md:flex-row
        flex-col
      "
    >
      <nuxt-link
        to="/"
        class="
          text-white
          md:px-3 md:py-1 md:my-2
          bg-transparent
          hover:bg-gray-800
          rounded
          md:ml-5
          sm:px-2
        sm:py-2
        sm:m-2
          uppercase
        "
        >Home</nuxt-link
      >
      <nuxt-link
        to="DownloadPage"
        class="
          text-white
          md:px-3 md:py-1 md:my-2
          bg-transparent
          hover:bg-gray-800
          rounded
          md:mx-5
          sm:px-2
        sm:py-2
        sm:m-2
          uppercase
        "
        >Install</nuxt-link
      >
      <nuxt-link
        to="DownloadPage"
        class="
          text-white
          md:px-3 md:py-1 md:my-2
          bg-transparent
          hover:bg-gray-800
          rounded
          md:mx-3
          sm:px-2
        sm:py-2
        sm:m-2
          uppercase
        "
        >About</nuxt-link
      >
      <nuxt-link
        to="LogInPage"
        class="
          md:px-3 md:py-1 md:my-1
          text-white
          bg-gray-900
          hover:bg-blue-600
          rounded
          md:ml-5
          sm:px-2
        sm:py-2
        sm:m-2
          uppercase
        "
        >Login</nuxt-link
      >
    </div>
  </div>
</template>

<script>
export default {
  name: 'MenuBar',
}
</script>




