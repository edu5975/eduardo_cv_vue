<template>
  <div class="page-content">
    <div>
      <ProfileTop/>
      <BasicInformation/>
      <ProfessionalSkills/>
      <Portfolio/>
      <Experience/>
      <Education/>
      <Courses/>
    </div>
  </div>
</template>

<script>
import ProfileTop from "./ProfileTop";
import BasicInformation from "./BasicInformation";
import ProfessionalSkills from "./ProfessionalSkills";
import Portfolio from "./Portfolio";
import Experience from "./Experience";
import Education from "./Education";
import Courses from "./Courses";
export default {
  name: 'Information',
  components: {
    Courses,
    Education,
    Experience,
    Portfolio,
    ProfessionalSkills,
    BasicInformation,
    ProfileTop
  }
}
</script>

<style>

</style>