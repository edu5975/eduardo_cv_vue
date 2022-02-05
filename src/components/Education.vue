<template>
  <div class="section" id="education">
    <div class="container cc-education">
      <div class="h4 text-center mb-4 title">Educación</div>
      <div class="card" v-for="edu in education" :key="edu">
        <div class="row">
          <div class="col-md-3 bg-primary" data-aos="fade-right" data-aos-offset="50" data-aos-duration="500">
            <div class="card-body cc-education-header">
              <p>{{edu.inicio}} - {{edu.final}}</p>
              <div class="h5">{{edu.level}}</div>
            </div>
          </div>
          <div class="col-md-9" data-aos="fade-left" data-aos-offset="50" data-aos-duration="500">
            <div class="card-body">
              <div class="h5">{{edu.career}}</div>
              <p class="category">{{edu.school}}</p>
              <p>{{edu.description}}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Education",
  data: function () {
    return {
      education:[
        {
          'inicio' : '2021',
          'final' : '2022',
          'career':'Ingeniería en Sistemas Computacionales',
          'school':'Instituto Tecnológico de Celaya',
          'level' :'Universidad',
          'description':`
Coordinar, supervisar y monitorear el buen funcionamiento y
operación normal de los sistemas. Participar activamente de la
implantación en producción de nuevos sistemas o cambios a los
existentes. Mantención y soporte de los sistemas que están en
operación.`
        },
        {
          'inicio' : '2014',
          'final' : '2017',
          'career':'Técnico en Programación',
          'school':'CETIS No. 115 mexicano-japonés',
          'level' :'Preparatoria',
          'description':`
Diseñar y programar sitios web y aplicaciones, ser el responsable de
definir la interfaz gráfica para que resulte atractiva al usuario.
Corregir los errores que se identifiquen y dar mantenimiento a los
proyectos.`
        },
      ]
    }
  }
}
</script>

<style scoped>

</style>