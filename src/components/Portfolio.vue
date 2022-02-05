<template>
  <div class="section" id="portfolio">
    <div class="container">
      <div class="row">
        <div class="col-md-6 ml-auto mr-auto">
          <div class="h4 text-center mb-4 title">Portfolio</div>
          <div class="nav-align-center">
            <ul class="nav nav-pills nav-pills-primary" role="tablist">
              <li class="nav-item" v-for="category in categories" :key="category">
                <a :class="'nav-link '+(category.id==1?'active':'')" data-toggle="tab" :href="'#'+category.ref" role="tablist">
                  <i class="fa fa-laptop" :class="'fa '+category.icon" aria-hidden="true"></i>
                </a>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="tab-content gallery mt-5">
        <div :class="'tab-pane '+(category.id==1?'active':'')" :id="category.ref" role="tabpanel" v-for="category in categories" :key="category">
          <div class="ml-auto mr-auto">
            <div class="row" >
              <div class="col-md-6" v-for="proyect in category.list" :key="proyect">
                <div class="cc-porfolio-image img-raised" data-aos="fade-up" data-aos-anchor-placement="top-bottom">
                  <a :href="proyect.href">
                    <figure class="cc-effect">
                      <img :src="'assets/images/'+proyect.img" alt="Image" />
                      <figcaption>
                        <div class="h4">{{proyect.name}}</div>
                        <p>{{proyect.description}}</p>
                      </figcaption>
                    </figure>
                  </a>
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
  name: "Portfolio",
  data: function () {
    return {
      categories : [
        {
          'id'  :1,
          'name':'Web Development',
          'ref' :'web-development',
          'icon':'fa-laptop',
          'list':[
            {
              'id' : 1,
              'href' : 'https://github.com/edu5975/Eduardo-Rico-CV',
              'img'  : 'web-1.jpg',
              'name' : 'CV',
              'description':'Eduardo Rico'
            },
            {
              'id' : 2,
              'href' : '#',
              'img'  : 'web-2.jpg',
              'name' : 'Hospital API',
              'description':'Api for a hospital development in Express.js'
            },
            {
              'id' : 3,
              'href' : 'https://github.com/edu5975/medicare-front',
              'img'  : 'web-3.jpg',
              'name' : 'Medicare Vue.js',
              'description':'Front of hospital API'
            },
            {
              'id' : 4,
              'href' : 'https://github.com/edu5975/library-php-mysql-html',
              'img'  : 'web-4.jpg',
              'name' : 'Library php-mysql-html',
              'description':'Front for a library with mysql database'
            },
            {
              'id' : 5,
              'href' : 'https://github.com/edu5975/congress-cisme-drupal',
              'img'  : 'web-5.jpg',
              'name' : 'Congress CISME in drupal',
              'description':'Web development for a congress in my university in drupal'
            },
          ]
        },
        {
          'id'  :2,
          'name':'Mobile Development',
          'ref' :'mobile-development',
          'icon':'fa-mobile',
          'list':[
            {
              'id' : 1,
              'href' : 'https://github.com/edu5975/pokedex-flutter',
              'img'  : 'mobile-1.jpg',
              'name' : 'Pokedex Flutter',
              'description':'Information of Pokemon'
            },
            {
              'id' : 2,
              'href' : 'https://github.com/edu5975/movies-flutter',
              'img'  : 'mobile-2.jpg',
              'name' : 'Movies Flutter',
              'description':'App of movies'
            },
            {
              'id' : 3,
              'href' : 'https://github.com/edu5975/flutter-barcode-scanner-and-generator',
              'img'  : 'mobile-3.jpg',
              'name' : 'Barcode Flutter',
              'description':'Scanner and generator of bar codes'
            },
            {
              'id' : 4,
              'href' : 'https://github.com/edu5975/weather-flutter',
              'img'  : 'mobile-4.jpg',
              'name' : 'Weather Flutter',
              'description':'App for the weather'
            },
          ]
        },
        {
          'id'  :3,
          'name':'Desktop',
          'ref' :'desktop-development',
          'icon':'fa-desktop',
          'list':[
            {
              'id' : 1,
              'href' : 'https://github.com/edu5975/compiler-simulator-java',
              'img'  : 'desktop-1.jpg',
              'name' : 'Lexical, syntactic and semantic analyzer',
              'description':'Development with Java in Netbeans IDE'
            },
            {
              'id' : 2,
              'href' : 'https://github.com/edu5975/library-java-mysql',
              'img'  : 'mobile-2.jpg',
              'name' : 'Library Java-Mysql',
              'description':'Library development with java and mysql in IntelliJ IDEA'
            },
            {
              'id' : 3,
              'href' : 'https://github.com/edu5975/money-counter-assembler',
              'img'  : 'mobile-3.jpg',
              'name' : 'Money counter in Assembler',
              'description':'Application created to count coins entered in a 3d printed object developed in assembler'
            },
            {
              'id' : 4,
              'href' : 'https://github.com/edu5975/robot-arduino-processing',
              'img'  : 'mobile-4.jpg',
              'name' : 'Robot with Arduino and Processing',
              'description':'Robot created using arduino and processing to be controlled remotely from a computer'
            },
          ]
        },
      ]
    }
  }
}
</script>

<style scoped>

</style>