<template>
  <header>
    <div class="profile-page sidebar-collapse">
      <nav class="navbar navbar-expand-lg fixed-top navbar-transparent bg-primary" color-on-scroll="400">
        <!--TOOLBAR-->
        <div class="container">
          <div class="navbar-translate">
            <a class="navbar-brand" href="#" rel="tooltip">Eduardo Rico</a>
            <button
                class="navbar-toggler navbar-toggler"
                type="button"
                data-toggle="collapse"
                data-target="#navigation"
                aria-controls="navigation"
                aria-expanded="false"
                aria-label="Toggle navigation"
            ><span class="navbar-toggler-bar bar1"></span
                ><span class="navbar-toggler-bar bar2"></span
            ><span class="navbar-toggler-bar bar3"></span>
            </button>
          </div>
          <div class="collapse navbar-collapse justify-content-end" id="navigation">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link smooth-scroll" href="#about">Acerca</a>
              </li>
              <li class="nav-item">
                <a class="nav-link smooth-scroll" href="#skill">Habilidades</a>
              </li>
              <li class="nav-item">
                <a class="nav-link smooth-scroll" href="#portfolio">Portafolio</a>
              </li>
              <li class="nav-item">
                <a class="nav-link smooth-scroll" href="#experience">Experiencia</a>
              </li>
              <li class="nav-item">
                <a class="nav-link smooth-scroll" href="#education">Educación</a>
              </li>
              <li class="nav-item">
                <a class="nav-link smooth-scroll" href="#courses">Cursos</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
  components: {
  }
}
</script>

<style>

</style>