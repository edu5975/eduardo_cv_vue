<template>
  <div class="section" id="about">
    <div class="container">
      <div class="card" data-aos="fade-up" data-aos-offset="10">
        <div class="row">
          <div class="col-lg-5 col-md-12">
            <div class="card-body">
              <div class="h4 mt-0 title">Acerca de mi</div>
              <p>Hola, soy @edu5975 mi nombre es Eduardo Rico</p>
              <p>
                Me gusta programar desde los 14 años. Soy Ingeniero en Sistemas Computacionales.
                Me gusta programar páginas web y tecnologías móviles. Actualmente estoy aprendiendo dart,
                flutter para dispositivos móviles y vue.js junto con node.js con Express para páginas web.
              </p>
            </div>
          </div>
          <div class="col-lg-4 col-md-12">
            <div class="card-body">
              <div class="h4 mt-0 title">Información básica</div>
              <div class="row">
                <div class="col-sm-5">
                  <strong class="text-uppercase">Edad:</strong>
                </div>
                <div class="col-sm-7">22</div>
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
                  <strong class="text-uppercase">Telefono:</strong>
                </div>
                <div class="col-sm-7">
                  <a href="tel:+524611842703">+524611842703</a>
                </div>
              </div>
              <div class="row mt-3">
                <div class="col-sm-5">
                  <strong class="text-uppercase">Idiomas:</strong>
                </div>
                <div class="col-sm-7">Español, Inglés</div>
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
          'Programador','Videojuegos','Natación','Ciclismo','Correr'
      ]
    }
  }
}
</script>

<style scoped>

</style>