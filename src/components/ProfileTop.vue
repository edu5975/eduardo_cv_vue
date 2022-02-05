<template>
  <div class="profile-page">
    <div class="wrapper">
      <div class="page-header page-header-small" filter-color="green">
        <div
            class="page-header-image"
            data-parallax="true"
            style="background-image: url('./assets/images/cc-bg-1.jpg')"
        ></div>
        <div class="container">
          <div class="content-center">
            <div class="cc-profile-image">
              <a href="#"><img src="/assets/images/eduardo.png" alt="Image" /></a>
            </div>
            <div class="h2 title">Eduardo Daniel Rico Gómez</div>
            <p class="category text-white">
              Ingeniero en Sistemas Computacionales
            </p>
            <a
                class="btn btn-primary smooth-scroll mr-2"
                href="mailto:edu.dan68@gmail.com"
                data-aos="zoom-in"
                data-aos-anchor="data-aos-anchor"
            >Contáctame</a>
          </div>
        </div>

        <!--LINKS-->
        <div class="section">
          <div class="container">
            <div class="button-container">
              <template v-for="red in redes_sociales" :key="red.id">
                <a
                    class="btn btn-default btn-round btn-lg btn-icon"
                    :href="red.href"
                    rel="tooltip"
                    :title="red.title"
                ><i :class="'fa '+red.icon"></i
                ></a>
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
  name: "ProfileTop",
  data: function () {
    return {
      redes_sociales: [
        {
          id:1,
          name:'linkedin',
          href:'https://www.linkedin.com/in/edu5975/',
          title:'Sígueme en LinkedIn',
          icon:'fa-linkedin'
        },
        {
          id:2,
          name:'github',
          href:'https://github.com/edu5975',
          title:'Sígueme en GitHub',
          icon:'fa-github'
        },
        {
          id:3,
          name:'facebook',
          href:'https://www.facebook.com/edu5975/',
          title:'Sígueme en Facebook',
          icon:'fa-facebook'
        },
        {
          id:4,
          name:'instagram',
          href:'https://www.instagram.com/edu5975x/',
          title:'Sígueme en Instagram',
          icon:'fa-instagram'
        }
      ]
    }
  }
}
</script>

<style scoped>

</style>