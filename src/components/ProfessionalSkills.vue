<template>
  <div class="section" id="skill">
    <div class="container">
      <div class="h4 text-center mb-4 title">Professional Skills</div>
      <div
          class="card"
          data-aos="fade-up"
          data-aos-anchor-placement="top-bottom"
      >
        <div class="card-body">
          <div class="container">
            <div class="row" >
              <div
                  class="col-md-2 col-4 image-container"
                  style="padding-bottom: 10px"
                  v-for="skill in skills" :key="skill"
              >
                <img
                    :src="'/assets/images/skills/'+skill.img"
                    alt="Image"
                    rel="tooltip"
                    :title="skill.title"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ProfessionalSkills",
  data: function () {
    return {
      skills:[
        { img:'js.png', title:'JavaScript' },
        { img:'html5.png', title:'HTML5' },
        { img:'css.png', title:'CSS' },
        { img:'bootstrap.png', title:'Bootstrap' },
        { img:'git.png', title:'Git' },
        { img:'npm.png', title:'NPM' },
        { img:'vue.png', title:'Vue.js' },
        { img:'nodejs.png', title:'Node.js' },
        { img:'flutter.png', title:'Flutter' },
        { img:'php.png', title:'PHP' },
        { img:'python.png', title:'Python' },
        { img:'mysql.png', title:'MySQL' },
        { img:'java.png', title:'Java' },
        { img:'postgres.png', title:'Postgres' },
        { img:'mongodb.png', title:'MongoBD' },
        { img:'arduino.png', title:'Arduino' },
        { img:'bash.png', title:'Bash' },
        { img:'office.png', title:'Office' }
      ]
    }
  }

}
</script>

<style scoped>

</style>