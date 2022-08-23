<template>
    <div  class="bg-gray-900 flex flex-col">
      <home-call-to-action title="Go Home In One Piece" description="Teach safety principles effectively with interactive 3D scenarios" callToAction="Sign Up"></home-call-to-action>

      <h2 class="text-white py-3 px-3 font-bold text-3x1">What is Avalon?</h2>

      <div class="lg:flex flex-row">
      <notice-card title="Quickly Create Scenes in 3D" message="Using Avalon's powerful 3D user interface, you can create complex safety scenarios by creating and editing a wide variety of construction assets"></notice-card>
      <notice-card title="Share Scenes with Your Team in the Cloud" message="All your scenes are saved in the cloud, so managing your scenarios and collaborating is frictionless"></notice-card>
      <notice-card title="Use Snapshots to Save Scenes" message="Part of Avalon's secret sauce is using snapshots to revisit different aspects of your scenarios either for a presentation or to recreate a screenshot"></notice-card>
      </div>
      <footer-component></footer-component>
    </div>
</template>

<script>
import FooterComponentVue from '~/components/FooterComponent.vue'
import HomeCallToActionVue from '~/components/HomeCallToAction.vue'
import NoticeCardVue from '~/components/NoticeCard.vue'
export default {
  name: 'IndexPage',
  components: [
    HomeCallToActionVue,
    NoticeCardVue,
    FooterComponentVue
  ]
}
</script>
