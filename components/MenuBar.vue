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
        justify-center
        md:py-2 md:mr-5
        flex
        md:flex-row
        flex-col
      "
    >
      <div class="hidden md:flex">
        <menu-bar-button name="Home" link="/"></menu-bar-button>
        <menu-bar-button name="Install" link="DownloadPage"></menu-bar-button>
        <menu-bar-button name="About" link="DownloadPage"></menu-bar-button>
        <menu-bar-button name="Login" link="LogInPage"></menu-bar-button>
      </div>
      <div class="sm:flex md:hidden my-5">
        <mobile-main-menu-drop-down></mobile-main-menu-drop-down>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MenuBar',
}
</script>


<style scoped>

</style>



