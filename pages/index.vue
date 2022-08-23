<template>
  <div class="bg-gray-900 flex flex-col">
    <home-call-to-action
      title="Go Home In One Piece"
      description="Teach safety principles effectively with interactive 3D scenarios"
      callToAction="Sign Up"
    ></home-call-to-action>

    <simple-header name="What is Avalon?"></simple-header>

    <div class="lg:flex flex-row  items-start">
      <notice-card
        title="Quickly Create Scenes in 3D"
        message="Using Avalon's powerful 3D user interface, you can create complex safety scenarios by creating and editing a wide variety of construction assets"
      ></notice-card>
      <notice-card
        title="Share Scenes with Your Team in the Cloud"
        message="All your scenes are saved in the cloud, so managing your scenarios and collaborating is frictionless"
      ></notice-card>
      <notice-card
        title="Use Snapshots to Save Scenes"
        message="Part of Avalon's secret sauce is using snapshots to revisit different aspects of your scenarios for a step-by-step slide presentation or to re-edit old screenshots"
      ></notice-card>
    </div>

    <simple-header name="How Does Avalon Work?"></simple-header>
    <div class="lg:flex flex-row items-start">
      <notice-card
        title="1. Create a Scenario"
        message="Create a new (or edit an existing) scenario using our massive construction library"
      ></notice-card>
      <notice-card
        title="Example"
        message="In 'fall protection' you could display a character falling off a building but was safe because he was tied off correctly"
      ></notice-card>
    </div>
    <div class="lg:flex flex-row  items-start">
      <notice-card
        title="2. Save to the cloud"
        message="Using the cloud you can share it with other collaborators or save it later. Also, when a mistake is found it's easy to go back and make a quick change."
      ></notice-card>
      <notice-card
        title="Example"
        message="In 'fall protection' a team member had the character tied off to a faulty anchor with an incorrect amount of screws. No big deal, since you logged in, just email him to add a few more screws."
      ></notice-card>
    </div>
    <div class="lg:flex flex-row items-start">
      <notice-card title="3. Present with Avalon" message="Once you've verified all the 3D slides (called snapshots) are correct, it's time to take it into the new-hire classroom."></notice-card>
      <notice-card title="Example" message="After finishing'fall protection' an intern will take screenshots and place them in a powerpoint for next week's job safety talk"></notice-card>
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
  components: [HomeCallToActionVue, NoticeCardVue, FooterComponentVue],
}
</script>
