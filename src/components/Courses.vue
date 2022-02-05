<template>
  <div class="section" id="courses">
    <div class="container cc-experience">
      <div class="h4 text-center mb-4 title">
        Cursos y Certificados
      </div>
      <div class="card" v-for="course in courses" :key="course">
        <div class="row">
          <div class="col-md-3 bg-primary" data-aos="fade-right" data-aos-offset="50" data-aos-duration="500">
            <div class="card-body cc-experience-header">
              <div class="h5">{{course.name}}</div>
            </div>
          </div>
          <div class="col-md-9" data-aos="fade-left" data-aos-offset="50" data-aos-duration="500">
            <div class="card-body">
              <div class="row">
                <div class="col-md-6" v-for="list in course.list" :key="list">
                  <p>{{list}}</p>
                </div>
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
  name: "Courses",
  data: function () {
    return {
      'courses':[
        {
          'id' : 1,
          'name': 'Google Activate',
          'list':[
              'Digital transformation for employment',
              'Cloud Computing',
              'Digital skills for professionals',
              'Mobile app development course',
              'Protect your business: Cybersecurity at work'
          ]
        },
        {
          'id' : 2,
          'name': 'Udemy',
          'list':[
            'Primeros pasos con Vue.js | Vue en ejercicios',
            'The Complete 2021 PHP Full Stack Web Developer Bootcamp',
            'Bootstrap & jQuery - Certification Course for Beginners',
            'Database Engineer/DBA - (PostgreSQL, IBM-DB2, MariaDB,NoSQL)',
            'Protect your business: Cybersecurity at work',
            'JavaScript, Bootstrap, & PHP - Certification for Beginners',
            'Curso Básico de Base de Datos MySQL con Linux'
          ]
        },
        {
          'id' : 3,
          'name': 'Cisco NetAcad',
          'list':[
            'Introduction to IoT',
            'Introduction to Cybersecurity',
            'CCNA R&S: Routing and Switching Essentials',
            'CCNA R&S: Scaling Networks',
            'CCNA Cybersecurity Operations',
          ]
        },
        {
          'id' : 4,
          'name': 'Certiprof',
          'list':[
            'Scrum Foundation Professional Certificate',
            'Cyber Security Foundation - CSFPC™ v.1.0',
            'Lifelong Learning',
          ]
        },
      ]
    }
  }
}
</script>

<style scoped>

</style>