<template>
  <div class="section" id="about">
    <div class="container">
      <div class="card" data-aos="fade-up" data-aos-offset="10">
        <div class="row">
          <div class="col-lg-5 col-md-12">
            <div class="card-body">
              <div class="h4 mt-0 title">About</div>
              <p>Hi, I’m @edu5975 My name is Eduardo Rico</p>
              <p>
                I like programming since I was 14 years old. I am
                currently studying computer systems engineering and I am
                close to finishing my studies. I like to program in web
                and mobile technologies. Currently I am learning dart,
                flutter for mobile and vue.js together with node.js with
                express for web pages.
              </p>
            </div>
          </div>
          <div class="col-lg-4 col-md-12">
            <div class="card-body">
              <div class="h4 mt-0 title">Basic Information</div>
              <div class="row">
                <div class="col-sm-5">
                  <strong class="text-uppercase">Age:</strong>
                </div>
                <div class="col-sm-7">21</div>
              </div>
              <div class="row mt-3">
                <div class="col-sm-5">
                  <strong class="text-uppercase">Email:</strong>
                </div>
                <div class="col-sm-7">
                  <a href="mailto:edu.dan68@gmail.com"
                  >edu.dan68@gmail.com</a
                  >
                </div>
              </div>
              <div class="row mt-3">
                <div class="col-sm-5">
                  <strong class="text-uppercase">Phone:</strong>
                </div>
                <div class="col-sm-7">
                  <a href="tel:+524611842703">+524611842703</a>
                </div>
              </div>
              <div class="row mt-3">
                <div class="col-sm-5">
                  <strong class="text-uppercase">Language:</strong>
                </div>
                <div class="col-sm-7">Spanish, English</div>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-12">
            <div class="card-body">
              <div class="h4 mt-0 title">Hobbies</div>
              <template v-for="hobbie in hobbies" :key="hobbie">
                <div class="row mt-3">
                  <div class="col-sm-12">{{hobbie}}</div>
                </div>
              </template>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BasicInformation",
  data: function () {
    return {
      hobbies:[
          'Programming','Videogames','Swimming','Ciclyng','Running'
      ]
    }
  }
}
</script>

<style scoped>

</style>