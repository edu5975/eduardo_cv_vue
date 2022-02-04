<template>
  <div class="page-content">
    <div>
      <ProfileTop/>
      <BasicInformation/>
      <ProfessionalSkills/>

      <!--PORTFOLIO-->
      <div class="section" id="portfolio">
        <div class="container">
          <div class="row">
            <div class="col-md-6 ml-auto mr-auto">
              <div class="h4 text-center mb-4 title">Portfolio</div>
              <div class="nav-align-center">
                <ul class="nav nav-pills nav-pills-primary" role="tablist">
                  <li class="nav-item">
                    <a
                        class="nav-link active"
                        data-toggle="tab"
                        href="#web-development"
                        role="tablist"
                    ><i class="fa fa-laptop" aria-hidden="true"></i
                    ></a>
                  </li>
                  <li class="nav-item">
                    <a
                        class="nav-link"
                        data-toggle="tab"
                        href="#mobile-development"
                        role="tablist"
                    ><i class="fa fa-mobile" aria-hidden="true"></i
                    ></a>
                  </li>
                  <li class="nav-item">
                    <a
                        class="nav-link"
                        data-toggle="tab"
                        href="#desktop-development"
                        role="tablist"
                    ><i class="fa fa-desktop" aria-hidden="true"></i
                    ></a>
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <!--MOBILE-->
          <div class="tab-content gallery mt-5">
            <div class="tab-pane" id="mobile-development" role="tabpanel">
              <div class="ml-auto mr-auto">
                <div class="row">
                  <div class="col-md-6">
                    <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                    >
                      <a href="https://github.com/edu5975/pokedex-flutter">
                        <figure class="cc-effect">
                          <img src="images/mobile-1.jpg" alt="Image" />
                          <figcaption>
                            <div class="h4">Pokedex Flutter</div>
                            <p>Information of Pokemon</p>
                          </figcaption>
                        </figure></a
                      >
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                    >
                      <a href="https://github.com/edu5975/movies-flutter">
                        <figure class="cc-effect">
                          <img src="images/mobile-2.jpg" alt="Image" />
                          <figcaption>
                            <div class="h4">Movies Flutter</div>
                            <p>App of movies</p>
                          </figcaption>
                        </figure></a
                      >
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-6">
                    <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                    >
                      <a
                          href="https://github.com/edu5975/flutter-barcode-scanner-and-generator"
                      >
                        <figure class="cc-effect">
                          <img src="images/mobile-3.jpg" alt="Image" />
                          <figcaption>
                            <div class="h4">Barcode Flutter</div>
                            <p>Scanner and generator of bar codes</p>
                          </figcaption>
                        </figure></a
                      >
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                    >
                      <a href="https://github.com/edu5975/weather-flutter">
                        <figure class="cc-effect">
                          <img src="images/mobile-4.jpg" alt="Image" />
                          <figcaption>
                            <div class="h4">Weather Flutter</div>
                            <p>App for the weather</p>
                          </figcaption>
                        </figure></a
                      >
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <!--ONLINE-->
            <div class="tab-pane active" id="web-development">
              <div class="ml-auto mr-auto">
                <div class="row">
                  <div class="col-md-6">
                    <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                    >
                      <a href="https://github.com/edu5975/Eduardo-Rico-CV">
                        <figure class="cc-effect">
                          <img src="images/web-1.jpg" alt="Image" />
                          <figcaption>
                            <div class="h4">CV</div>
                            <p>Eduardo Rico</p>
                          </figcaption>
                        </figure></a
                      >
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                    >
                      <a href="#web-development">
                        <figure class="cc-effect">
                          <img src="images/web-2.jpg" alt="Image" />
                          <figcaption>
                            <div class="h4">Hospital API</div>
                            <p>
                              Api for a hospital development in Express.js
                            </p>
                          </figcaption>
                        </figure>
                      </a>
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-6">
                    <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                    >
                      <a href="https://github.com/edu5975/medicare-front">
                        <figure class="cc-effect">
                          <img src="images/web-3.jpg" alt="Image" />
                          <figcaption>
                            <div class="h4">Medicare Vue.js</div>
                            <p>Front of hospital API</p>
                          </figcaption>
                        </figure></a
                      >
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                    >
                      <a
                          href="https://github.com/edu5975/library-php-mysql-html"
                      >
                        <figure class="cc-effect">
                          <img src="images/web-4.jpg" alt="Image" />
                          <figcaption>
                            <div class="h4">Library php-mysql-html</div>
                            <p>Front for a library with mysql database</p>
                          </figcaption>
                        </figure>
                      </a>
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-6">
                    <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                    >
                      <a
                          href="https://github.com/edu5975/congress-cisme-drupal"
                      >
                        <figure class="cc-effect">
                          <img src="images/web-5.jpg" alt="Image" />
                          <figcaption>
                            <div class="h4">Congress CISME in drupal</div>
                            <p>
                              Web development for a congress in my university
                              in drupal
                            </p>
                          </figcaption>
                        </figure></a
                      >
                    </div>
                  </div>
                  <!--
                  <div class="col-md-6">
                    <div
                      class="cc-porfolio-image img-raised"
                      data-aos="fade-up"
                      data-aos-anchor-placement="top-bottom"
                    >
                      <a href="#web-development">
                        <figure class="cc-effect">
                          <img src="images/web-2.jpg" alt="Image" />
                          <figcaption>
                            <div class="h4">Hospital API</div>
                            <p>
                              Api for a hospital development in Express.js
                            </p>
                          </figcaption>
                        </figure>
                      </a>
                    </div>
                  </div>-->
                </div>
              </div>
            </div>
            <!--DESKTOP-->
            <div class="tab-pane" id="desktop-development" role="tabpanel">
              <div class="ml-auto mr-auto">
                <div class="row">
                  <div class="col-md-6">
                    <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                    >
                      <a
                          href="https://github.com/edu5975/compiler-simulator-java"
                      >
                        <figure class="cc-effect">
                          <img src="images/desktop-1.jpg" alt="Image" />
                          <figcaption>
                            <div class="h4">
                              Lexical, syntactic and semantic analyzer
                            </div>
                            <p>Development with Java in Netbeans IDE</p>
                          </figcaption>
                        </figure></a
                      >
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                    >
                      <a href="https://github.com/edu5975/library-java-mysql">
                        <figure class="cc-effect">
                          <img src="images/desktop-2.jpg" alt="Image" />
                          <figcaption>
                            <div class="h4">Library Java-Mysql</div>
                            <p>
                              Library development with java and mysql in
                              IntelliJ IDEA
                            </p>
                          </figcaption>
                        </figure></a
                      >
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-6">
                    <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                    >
                      <a
                          href="https://github.com/edu5975/money-counter-assembler"
                      >
                        <figure class="cc-effect">
                          <img src="images/desktop-3.jpg" alt="Image" />
                          <figcaption>
                            <div class="h4">Money counter in Assembler</div>
                            <p>
                              Application created to count coins entered in a
                              3d printed object developed in assembler
                            </p>
                          </figcaption>
                        </figure></a
                      >
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div
                        class="cc-porfolio-image img-raised"
                        data-aos="fade-up"
                        data-aos-anchor-placement="top-bottom"
                    >
                      <a
                          href="https://github.com/edu5975/robot-arduino-processing"
                      >
                        <figure class="cc-effect">
                          <img src="images/desktop-4.jpg" alt="Image" />
                          <figcaption>
                            <div class="h4">
                              Robot with Arduino and Processing
                            </div>
                            <p>
                              Robot created using arduino and processing to be
                              controlled remotely from a computer
                            </p>
                          </figcaption>
                        </figure></a
                      >
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!--EXPERIENCE-->
      <div class="section" id="experience">
        <div class="container cc-experience">
          <div class="h4 text-center mb-4 title">Work Experience</div>
          <div class="card">
            <div class="row">
              <div
                  class="col-md-3 bg-primary"
                  data-aos="fade-right"
                  data-aos-offset="50"
                  data-aos-duration="500"
              >
                <div class="card-body cc-experience-header">
                  <p>April 2017 - February 2018</p>
                  <div class="h5">Telcel</div>
                </div>
              </div>
              <div
                  class="col-md-9"
                  data-aos="fade-left"
                  data-aos-offset="50"
                  data-aos-duration="500"
              >
                <div class="card-body">
                  <div class="h5">Promoter</div>
                  <p>
                    Seller in equipment and plans of the telephone company
                    Telcel.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!--EDUCATION-->
      <div class="section" id="education">
        <div class="container cc-education">
          <div class="h4 text-center mb-4 title">Education</div>
          <div class="card">
            <div class="row">
              <div
                  class="col-md-3 bg-primary"
                  data-aos="fade-right"
                  data-aos-offset="50"
                  data-aos-duration="500"
              >
                <div class="card-body cc-education-header">
                  <p>2017 - In progress</p>
                  <div class="h5">University</div>
                </div>
              </div>
              <div
                  class="col-md-9"
                  data-aos="fade-left"
                  data-aos-offset="50"
                  data-aos-duration="500"
              >
                <div class="card-body">
                  <div class="h5">Computer Systems Engineer</div>
                  <p class="category">
                    Instituto Tecnológico Nacional de México en Celaya
                  </p>
                  <p>
                    Computer Systems Engineering is responsible for the
                    design, programming, implementation and maintenance of
                    systems. The correct study of Computer Systems Engineering
                    will lead the professional to know all the application
                    possibilities that it has in their professional
                    development. You will also know how to respect
                    intellectual property and see the value that teamwork has
                    in this profession.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="card">
            <div class="row">
              <div
                  class="col-md-3 bg-primary"
                  data-aos="fade-right"
                  data-aos-offset="50"
                  data-aos-duration="500"
              >
                <div class="card-body cc-education-header">
                  <p>2014 - 2017</p>
                  <div class="h5">Preparatory</div>
                </div>
              </div>
              <div
                  class="col-md-9"
                  data-aos="fade-left"
                  data-aos-offset="50"
                  data-aos-duration="500"
              >
                <div class="card-body">
                  <div class="h5">Programming technician</div>
                  <p class="category">CETIS no. 115 mexicano-japonés</p>
                  <p>
                    The Technological Baccalaureate with a specialty in
                    Programming Technician offers the professional
                    competencies that allow the student to carry out
                    activities aimed at: analyzing, designing, developing,
                    installing and maintaining application software based on
                    user requirements.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!--COURSES-->
      <div class="section" id="courses">
        <div class="container cc-experience">
          <div class="h4 text-center mb-4 title">
            Courses and certificates
          </div>
          <div class="card">
            <div class="row">
              <div
                  class="col-md-3 bg-primary"
                  data-aos="fade-right"
                  data-aos-offset="50"
                  data-aos-duration="500"
              >
                <div class="card-body cc-experience-header">
                  <div class="h5">Google Activate</div>
                </div>
              </div>
              <div
                  class="col-md-9"
                  data-aos="fade-left"
                  data-aos-offset="50"
                  data-aos-duration="500"
              >
                <div class="card-body">
                  <div class="row">
                    <div class="col-md-6">
                      <p>Digital transformation for employment</p>
                      <p>Cloud Computing</p>
                      <p>Digital skills for professionals</p>
                    </div>
                    <div class="col-md-6">
                      <p>Mobile app development course</p>
                      <p>Protect your business: Cybersecurity at work</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="card">
            <div class="row">
              <div
                  class="col-md-3 bg-primary"
                  data-aos="fade-right"
                  data-aos-offset="50"
                  data-aos-duration="500"
              >
                <div class="card-body cc-experience-header">
                  <div class="h5">Udemy</div>
                </div>
              </div>
              <div
                  class="col-md-9"
                  data-aos="fade-left"
                  data-aos-offset="50"
                  data-aos-duration="500"
              >
                <div class="card-body">
                  <div class="row">
                    <div class="col-md-12">
                      <p>Learn Git From Scratch with Hands-on Exercises</p>
                      <p>
                        The Complete 2021 PHP Full Stack Web Developer
                        Bootcamp
                      </p>
                      <p>Basic Course of MySQL Database with Linux</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="card">
            <div class="row">
              <div
                  class="col-md-3 bg-primary"
                  data-aos="fade-right"
                  data-aos-offset="50"
                  data-aos-duration="500"
              >
                <div class="card-body cc-experience-header">
                  <div class="h5">Cisco</div>
                </div>
              </div>
              <div
                  class="col-md-9"
                  data-aos="fade-left"
                  data-aos-offset="50"
                  data-aos-duration="500"
              >
                <div class="card-body">
                  <div class="row">
                    <div class="col-md-12">
                      <p>Introduction to Cybersecurity</p>
                      <p>CCNA Routing and Switching: Scaling Networks</p>
                      <p>
                        CCNA Routing and Switching: Routing and Switching
                        Essentials
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="card">
            <div class="row">
              <div
                  class="col-md-3 bg-primary"
                  data-aos="fade-right"
                  data-aos-offset="50"
                  data-aos-duration="500"
              >
                <div class="card-body cc-experience-header">
                  <div class="h5">Certiprof</div>
                </div>
              </div>
              <div
                  class="col-md-9"
                  data-aos="fade-left"
                  data-aos-offset="50"
                  data-aos-duration="500"
              >
                <div class="card-body">
                  <div class="row">
                    <div class="col-md-12">
                      <p>Scrum Foundation Professional Certificate</p>
                      <p>Cyber Security Foundation - CSFPC™ v.1.0</p>
                      <p>Lifelong Learning</p>
                    </div>
                  </div>
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
import ProfileTop from "./ProfileTop";
import BasicInformation from "./BasicInformation";
import ProfessionalSkills from "./ProfessionalSkills";
export default {
  name: 'Information',
  components: {
    ProfessionalSkills,
    BasicInformation,
    ProfileTop
  }
}
</script>

<style>

</style>