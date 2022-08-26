<template>
  <div class="bg-gray-900 flex flex-col">
    <home-call-to-action
      title="Go Home In One Piece"
      description="Teach safety principles effectively with interactive 3D scenarios"
      callToAction="Sign Up"
    ></home-call-to-action>

    <div>
      <simple-header name="What is Avalon?"></simple-header>
      <div class="lg:flex flex-row items-start">
        <notice-card
          icon="fas fa-wrench text-white pr-2 mt-1"
          title="Quickly Create Scenes in 3D"
          message="Using Avalon's powerful 3D user interface, you can create complex safety scenarios by creating and editing a wide variety of construction assets"
        ></notice-card>
        <notice-card
          icon="fas fa-cloud text-white pr-2 mt-1"
          title="Share Scenes with Your Team in the Cloud"
          message="All your scenes are saved in the cloud, so managing your scenarios and collaborating is frictionless"
        ></notice-card>
        <notice-card
          icon="fas fa-camera text-white pr-2 mt-1"
          title="Use Snapshots to Save Scenes"
          message="Part of Avalon's secret sauce is using snapshots to revisit different aspects of your scenarios for a step-by-step slide presentation or to re-edit old screenshots"
        ></notice-card>
      </div>
    </div>
    <div class="bg-slate-800">
      <simple-header name="How Does Avalon Work?"></simple-header>
      <div class="my-5">
        <div class="flex flex-row my-5">
          <div class="flex-1">
            <p class="text-center text-slate-300">
              <span class="fas fa-bullhorn text-slate-300 mr-1"></span
              >Description
            </p>
          </div>
          <div class="flex-1">
            <p class="text-center text-slate-300">
              <span class="fas fa-comment text-slate-300 mr-1"></span>Example
            </p>
          </div>
        </div>
        <concept-example-card
          title="1. Create a Scenario"
          description="Create a new (or edit an existing) scenario using our massive construction library"
          exampleTitle="'Fall Protection'"
          exampleDescription="The Safety Trainer could display a character falling off a building but was safe because he was tied off correctly"
        ></concept-example-card>
        <concept-example-card
          title="2. Save to the cloud"
          description="Using the cloud you can share it with other collaborators or save it later. Also, when a mistake is found it's easy to go back and make a quick change."
          exampleTitle="Making Quick Changes to 'Fall Protection'"
          exampleDescription="A team member had the character tied off to a faulty anchor with an incorrect amount of screws. No big deal, since you logged in, just email him to add a few more screws."
        ></concept-example-card>
        <concept-example-card
          title="3. Present with Avalon"
          description="Once you've verified all the 3D slides (called snapshots) are correct, it's time to take it into the new-hire classroom."
          exampleTitle="Presenting 'Fall Protection'"
          exampleDescription="An intern will take screenshots and place them in a powerpoint for next week's job safety talk"
        ></concept-example-card>
      </div>
    </div>
    <simple-header name="How To Get Avalon"></simple-header>
    <notice-card
      icon="fas fa-hourglass text-white pr-2 mt-1"
      title="Avalon is not out yet"
      message="Right now our heads are down to the grind stone, getting ready for our first evaluation with some interested parties."
    ></notice-card>
    <simple-header name="Avalon Development Timeline"></simple-header>
    <div class="my-5 mx-10">
      <ol class="border-l border-gray-300">
        <time-line-component
          date="8.30.2022"
          title="Backend"
          description="Focusing on putting the very backend together so that the could persistance will work, right off the bat"
        >
        </time-line-component>
        <time-line-component
          date="9.15.2022"
          title="Alpha Released"
          description="The alpha version of avalon will be released to a few interested parties for evaluation. If you would like to participate contact the lead developer (howelltaylor195@gmail.com)"
        ></time-line-component>
        <time-line-component
          date="12.10.2022"
          title="Avalon Beta Public Preview"
          description="Avalon will be made available to the general public "
        ></time-line-component>
      </ol>
    </div>
    <footer-component></footer-component>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

    SimpleHeader
