<template>
  <div class="section" id="experience">
    <div class="container cc-experience">
      <div class="h4 text-center mb-4 title">Experiencia</div>
      <div class="card" v-for="experience in experiences" :key="experience">
        <div class="row">
          <div class="col-md-3 bg-primary" data-aos="fade-right" data-aos-offset="50" data-aos-duration="500">
            <div class="card-body cc-experience-header">
              <p>{{experience.inicio}} - {{experience.final}}</p>
              <div class="h5">{{experience.company}}</div>
            </div>
          </div>
          <div class="col-md-9" data-aos="fade-left" data-aos-offset="50" data-aos-duration="500">
            <div class="card-body">
              <div class="h5">{{experience.place}}</div>
              <p>{{experience.description}}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Experience",
  data: function () {
    return {
      experiences:[
        {
          'inicio' : '2021',
          'final' : 'Actual',
          'company':'CIDECUC',
          'place':'Desarrollador Jr.',
          'description':`
Desarrollo de un sistema ERP para satisfacer las necesidades de
multiples empresas haciendo uso de tecnologías de desarrollo Web
como lo son HTML5, CSS y JavaScript del lado del cliente y PHP con
el Framework Laravel junto a la base de datos PostgreSQL del lado
del servidor.`
        },
        {
          'inicio' : '2018',
          'final' : '2021',
          'company':'GALGO',
          'place':'Soporte Técnico',
          'description':`
Proporcionar asistencia a los usuarios al tener algún problema al
utilizar un producto o servicio, ya sea este de hardware o software
de una computadora, periféricos o artículos electrónicos. Instalar y
configurar puntos de venta en multiples sucursales.`
        },
        {
          'inicio' : '2017',
          'final' : '2018',
          'company':'Telcel',
          'place':'Promotor',
          'description':`
Representar a la empresa telefónica Telcel promoviendo los
distintos dispositivos y planes telefónicos, dar información a los
clientes sobre las características de los productos, resolver dudas,
asesorar sobre su uso, con el fin de lograr el objetivo de ventas
establecido por la compañía.`
        },
      ]
    }
  }
}
</script>

<style scoped>

</style>