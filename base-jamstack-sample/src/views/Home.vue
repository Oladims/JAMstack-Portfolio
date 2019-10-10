<template>
  <main>
      <div class="site">
        <!-- <app-header /> -->
        <div class="switch-wrapper">
        <div class="sun"></div>
        <div class="toggle-wrapper">
          <input id="switch" type="checkbox" />
          <label for="switch" id="toggle">Toggle</label>
        </div>
        <div class="moon"></div>
      </div>
        <app-header />
        <app-section-background />
        <app-section-skills />
        <app-section-experience />
        <app-section-featured />
        <app-section-Other-projects />
    <!-- <app-masthead /> -->
      </div>
  </main>
        
</template>

<script>
// import AppMasthead from "@/components/AppMasthead.vue";
// import AppForm from "@/components/AppForm.vue";
import AppHeader from "@/components/AppHeader.vue";
import AppSectionBackground from "@/components/AppSectionBackground.vue";
import AppSectionSkills from "@/components/AppSectionSkills.vue";
import AppSectionExperience from "@/components/AppSectionExperience.vue";
import AppSectionFeatured from "@/components/AppSectionFeatured.vue";
import AppSectionOtherProjects from "@/components/AppSectionOtherProjects.vue";

export default {
  components: {
    // AppMasthead,
    AppHeader,
    AppSectionBackground,
AppSectionSkills,
AppSectionExperience,
AppSectionFeatured,
AppSectionOtherProjects,
  }
};
</script>

<style lang="css">

</style>