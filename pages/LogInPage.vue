<template>
<div  class="bg-gray-900 pt-1 h-screen">
  <menu-bar></menu-bar>
  <footer-component></footer-component>
</div>
</template>

<script>
import FooterComponentVue from '~/components/FooterComponent.vue'
import MenuBarVue from '~/components/MenuBar.vue'
export default {
  name: "LoginPage",
  components: [
    FooterComponentVue,
    MenuBarVue,

  ]
}
</script>

