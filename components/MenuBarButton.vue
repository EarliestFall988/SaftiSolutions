<template>
  <nuxt-link
    :to="link"
    class="
      px-2
      py-2
      m-2
      text-white
      md:px-3 md:py-1 md:my-2
      bg-transparent
      hover:bg-gray-800
      rounded
      md:ml-5
      uppercase
    "
    >{{ name }}</nuxt-link
  >
</template>

<script>
export default {
  name: 'MenuBarButton',
  props: {
    name: {
      type: String,
      default: '',
    },
    link: {
      type: String,
      default: '',
    },
  },
}
</script>

