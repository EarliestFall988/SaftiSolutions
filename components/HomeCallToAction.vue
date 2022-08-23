<template>
  <div
    class="
      p-12
      mb-5
      text-center
      relative
      overflow-hidden
      bg-no-repeat bg-cover
      rounded-lg
    "
    style="background-image: url('/images/twist.jpg'); height: 700px"
  >
    <div
      class="
        absolute
        top-0
        right-0
        bottom-0
        left-0
        w-full
        h-full
        overflow-hidden
        bg-gradient-to-t
        from-gray-900
        to-transparent
      "
    >
      <menu-bar></menu-bar>
      <div class="flex justify-center items-center mt-10 md:h-full">
        <div class="text-white">
          <h2 class="font-semibold text-4xl mb-4">{{ title }}</h2>
          <h4 class="font-semibold text-xl mb-6">{{ description }}</h4>
          <a
            class="
              inline-block
              px-7
              py-3
              mb-1
              border-2 border-gray-50
              text-white
              bg-blue-800
              font-medium
              text-sm
              leading-snug
              uppercase
              rounded
              hover:bg-gradient-to-r from-blue-600 to-green-600
              hover:px-10
              transition
              duration-150
              ease-in-out
            "
            href="#!"
            role="button"
            data-mdb-ripple="true"
            data-mdb-ripple-color="light"
            >{{ callToAction }}</a
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeCallToAction',
  props: {
    title: {
      type: String,
      default: ''
    },
    description: {
      type: String,
      default: ''
    },
    callToAction: {
      type: String,
      default: ''
    },
  },
}
</script>

