<template>
  <div class="home container-fluid full-height">
    <div class="navbar mt-0 row justify-content-between">
      <div class="col-6 d-flex justify-content-start">
        <img src="../assets/NAGASE.png" alt="red-logo" />
      </div>
      <div class="col-6 d-flex justify-content-end">
        <p class="navbar-text">Make your Bussiness Shine</p>
      </div>
    </div>
    <!-- Landing -->
    <div class="row">
      <div class="landing full-height container-fluid">
        <div class="col-lg-6 col-md-12 d-inline-block">
          <h1 class="title">Acceleration Through Collaboration</h1>
        </div>
        <div class="col-lg-6 col-md-12 d-inline-block text-left">
          <h2 class="subtitle">
            EMPOWER YOUR PEOPLE AND PROJECTS WITH NAGASE BUSINESS SERVICES
          </h2>
          <p class="text-epi">
            Leveraging years of experience in international Specialty Chemicals
            sales and marketing combined with a global network of over 100
            Nagase Group® companies, NAGASE Business Services brings light to
            your project lifecycle through accelerated access to a spectrum of
            services:
          </p>
          <p class="text-epi-bold">
            Materials Development, Production, Marketing, Regulatory, and
            Deployment.
          </p>
          <p class="text-epi">
            Our goal is to be more than just your investor, incubator, toll
            producer or marketer.
          </p>
          <p class="text-epi-bold">We want to become your collaborator.</p>
        </div>
        <div class="col-12 d-flex justify-content-center">
          <div type="button" class="btn btn-primary click">
            <a href="#more" style="text-decoration: none; color: "
              >CLICK TO LEARN MORE</a
            >
          </div>
        </div>
      </div>
    </div>

    <!-- Cards Swiper -->
    <!-- <card-carousel/> -->

    <!-- Cards -->
    <div class="cards container-fluid full-height">
      <div class="cards-title d-flex justify-content-center">
        <div style="width: 920px" class="">
          <h1 class="subtitle text-center align-self-center" id="more">
            NAGASE BUSINESS SERVICES OFFERS A SPECTRUM OF A-LA-CARTE OR 360
            SERVICES TO BRING YOUR PROJECTS TO THEIR FULL POTENTIAL
          </h1>
        </div>
      </div>
      <div class="row mt-5 mb-5">
        <div class="col-sm-12">
          <div
            id="carouselExampleIndicators"
            class="carousel slide"
            data-bs-ride="carousel"
          >
            <div class="carousel-indicators">
              <button
                type="button"
                data-bs-target="#carouselExampleIndicators"
                data-bs-slide-to="0"
                class="active"
                aria-current="true"
                aria-label="Slide 1"
              ></button>
              <button
                type="button"
                data-bs-target="#carouselExampleIndicators"
                data-bs-slide-to="1"
                aria-label="Slide 2"
              ></button>
              <button
                type="button"
                data-bs-target="#carouselExampleIndicators"
                data-bs-slide-to="2"
                aria-label="Slide 3"
              ></button>
            </div>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <div class="row justify-content-center
                " style="flex-wrap:none;">
                  <div class="col-md-5">
                    <div class="card" style="" id="materials">
                      <div class="card-body">
                        <h5 class="card-title">Materials Development</h5>
                        <p class="card-text">
                          Nagase’s team of material science experts can develop
                          a wide array of technologies that will allow you to
                          rapidly iterate your ideas into viable materials. Our
                          state-of-the-art advanced materials facility is
                          centrally located in the US for maximum efficiency in
                          delivering turnkey solutions.
                        </p>
                        <ul class="cards-options">
                          <li>IDEA-TO-PRODUCT</li>
                          <li>PRODUCT-MARKET FIT</li>
                          <li>DE-RISKING</li>
                        </ul>
                      </div>
                    </div>
                  </div>
                  <div class="col-md-5">
                    <div class="card" id="production" style="">
                      <div class="card-body">
                        <h5 class="card-title">Production</h5>
                        <p class="card-text">
                          As part of its global production network, Nagase has
                          facilities in the US that provide toll manufacturing
                          support. NBS leverages those capabilities to offer you
                          customized support that best fits your production
                          needs, be it at lab, pilot, or commercial scale.
                        </p>
                        <ul class="cards-options">
                          <li>SCALE UP</li>
                          <li>CUSTOM MANUFACTURING</li>
                          <li>PROCESS OPTIMIZATION</li>
                        </ul>
                      </div>
                    </div>
                  </div>
                  
                </div>
              </div>
              <div class="carousel-item">
                <div class="row justify-content-center">
                  <div class="col-md-5">
                    <div class="card" id="marketing" style="">
                      <div class="card-body">
                        <h5 class="card-title">Marketing</h5>
                        <p class="card-text">
                          NAGASE Business Services is your trusted partner to
                          investigate new end-usages and verticals, obtain
                          customer voice feedback, and generate viable
                          application data. In addition, NBS uses a variety of
                          proven methods and tools to tailor campaigns that
                          maximize commercial opportunities domestically or
                          internationally.
                        </p>
                        <ul class="cards-options">
                          <li>GO-TO MARKET IMPLEMENTATION</li>
                          <li>MARKET IMPLEMENTATION</li>
                          <li>LEAD GENERATION</li>
                        </ul>
                      </div>
                    </div>
                  </div>
                  <div class="col-md-5">
                    <div class="card" id="regulatory" style="">
                      <div class="card-body">
                        <h5 class="card-title">Regulatory</h5>
                        <p class="card-text">
                          Through its extensive international distribution
                          business, Nagase has developed an intimate regulatory
                          knowledge that provides you with the assurance that
                          all compliance aspects will be fully managed. Also,
                          NBS has detailed experience in registration
                          requirements when introducing new chemical products to
                          verticals around the world.
                        </p>
                        <ul class="cards-options">
                          <li>PRODUCT REGISTRATION</li>
                          <li>IMPORT/EXPORT COMPLIANCE</li>
                        </ul>
                      </div>
                    </div>
                  </div>
                  
                </div>
              </div>
              <div class="carousel-item">
                <div class="row justify-content-center">
                    <div class="col-md-5">
                    <div class="card" id="deploy" style="">
                      <div class="card-body">
                        <h5 class="card-title">Deployment</h5>
                        <p class="card-text">
                          Our sales forces are technical experts who understand
                          your products and invest themselves in their promotion
                          and growth. When your project reaches commercial
                          success, NBS is your partner to guarantee your
                          materials are delivered anywhere in the world on time
                          every time using our extensive experience in domestic
                          and international logistics.
                        </p>
                        <ul class="cards-options">
                          <li>DISTRIBUTION</li>
                          <li>GLOBAL SALES REACH</li>
                          <li>WAREHOUSING</li>
                          <li>LOGISTICS</li>
                        </ul>
                      </div>
                    </div>
                  </div>
                </div>
                
              </div>
            </div>
            <button
              class="carousel-control-prev"
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide="prev"
            >
              <span
                class="carousel-control-prev-icon"
                aria-hidden="true"
              ></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button
              class="carousel-control-next"
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide="next"
            >
              <span
                class="carousel-control-next-icon"
                aria-hidden="true"
              ></span>
              <span class="visually-hidden">Next</span>
            </button>
          </div>
        </div>
      </div>
    </div>

    <!-- Contact Form -->
    <div class="full-height container-fluid">
      <div class="contact-form d-flex justify-content-center">
        <div class="row align-items-center">
          <h1 class="title">Make Your Business Shine</h1>
          <div class="col-sm-12 col-md-6">
            <h1 class="subtitle2">
              WITH NBS IN YOUR CORNER, THE POSSIBILITIES ARE ENDLESS
            </h1>
            <p class="text-epi">
              Connect with us and explore what NAGASE Business Services can do
              for your project. Whether you have a material that’s ready to
              scale and need a better understanding of its market and
              applications or you want to commercialize it but are unsure about
              regulatory requirements, NBS can empower your organization with
              flexible solutions tailored to your specific needs.
            </p>
            <p class="text-epi-bold">
              Please fill out the contact form and one of our experts will reach
              out to you soon.
            </p>
          </div>
          <div class="col-sm-12 col-md-6">
            <form>
              <div class="row">
                <div class="col-md-6 col-sm-12 d-inline-block">
                  <input
                    type="text"
                    class="form-control"
                    id="inputName"
                    placeholder="Name*"
                  />
                </div>
                <div class="col-md-6 col-sm-12 d-inline-block">
                  <input
                    type="text"
                    class="form-control"
                    id="inputCountry"
                    placeholder="Country*"
                  />
                </div>
              </div>
              <div class="row">
                <div class="col-md-6 col-sm-12 d-inline-block">
                  <input
                    type="text"
                    class="form-control"
                    id="inputCompany"
                    placeholder="Company"
                  />
                </div>
                <div class="col-md-6 col-sm-12 d-inline-block">
                  <input
                    type="email"
                    class="form-control"
                    id="inputEmail"
                    placeholder="Email Address"
                  />
                </div>
              </div>
              <div class="row">
                <div class="col-md-6 col-sm-12 d-inline-block">
                  <input
                    type="text"
                    class="form-control"
                    id="inputJob"
                    placeholder="Job Title"
                  />
                </div>
                <div class="col-md-6 col-sm-12 d-inline-block">
                  <input
                    type="text"
                    class="form-control"
                    id="inputContact"
                    placeholder="Contact Number*"
                  />
                </div>
              </div>
              <div class="row">
                <div class="col-sm-12 col-md-6 d-flex justify-content-center">
                  <button
                    type="submit"
                    class="btn btn-primary click-submit m-2"
                  >
                    CLICK AND SUBMIT
                  </button>
                </div>
                <div class="col-sm-12 col-md-6">
                  <h3 class="note m-3">*Requiered Fields</h3>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
      <!-- Footer -->
      <div class="footer container-fluid">
        <div class="row">
          <div class="col-sm-6 col-md-3">
            <h2 class="footer-title">NAGASE BUSINESS SERVICES</h2>
            <p class="footer-subtitle">©2022 Nagase Business Services</p>
            <p class="footer-subtitle">All Rights Reserved</p>
          </div>
          <div class="col-sm-6 col-md-4">
            <p class="text-epi">450 E. Devon Avenue Suite 300</p>
            <p class="text-epi">Itasca, IL 60143</p>
            <p class="text-epi">nbs@nagase-nam.com</p>
          </div>
          <div class="col-sm-12 col-md-5">
            <ul>
              <li><a href="" class="footer-link">PRIVACY</a></li>
              <li><a href="" class="footer-link">COOKIE POLICY</a></li>
              <li><a href="#top" class="footer-link">BACK TO TOP </a></li>
              <fa icon="fa-duotone fa-angles-up" />
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
//importing bootstrap 5
import * as Bootstrap from "bootstrap";

export default {
  name: "Home",
  mounted() {
    var myCarousel = document.querySelector("#myCarousel");
    new Bootstrap.Carousel(myCarousel);
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
/* Flickity Cards */

.navbar-text {
  color: #f2dda1;
  font-family: "Calibre Bold";
  font-size: 22px;
}
.title {
  font-family: "Epicene Text Bold";
  font-size: 100px;
  text-align: left;
  color: #ffffff;
}

.subtitle {
  font-family: "Calibre Bold";
  font-size: 30px;
  color: #a1a9d6;
  text-align: left;
}

.subtitle2 {
  font-family: "Calibre Bold";
  font-size: 40px;
  color: #ebb3a3;
  text-align: left;
}

.text-epi {
  font-family: "Epicene Text";
  font-size: 20px;
  text-align: left;
  color: #ffffff;
}

.text-epi-bold {
  font-family: "Epicene Text Bold";
  font-size: 20px;
  text-align: left;
  color: #ffffff;
}

.click,
.click > a {
  color: #1a1818 !important;
  background-color: #c7cdeb !important;
  border-radius: 0px !important;
  font-family: "Calibre Bold";
  font-size: 22px;
  float: left;
  border: 0px !important;
}

.click-submit {
  color: #1a1818 !important;
  background-color: #f2d0c7 !important;
  border-radius: 0px !important;
  font-family: "Calibre Bold";
  font-size: 22px;
  float: left;
  border: 0px !important;
}

.note {
  font-family: "Calibre Bold";
  font-size: 20px;
  color: #ffffff;
}

.landing {
  padding-right: 80px !important;
  padding-left: 80px !important;
}

input {
  background-color: #ffffff;
  opacity: 80%;
  color: #1a1818 !important;
  border-radius: 0px !important;
  border: #707070 1px;
  margin: 10px !important;
}

.contact-form {
  padding: 116px;
}

.footer {
  padding: 140px !important;
}

.footer-title {
  font-family: "Calibre Bold";
  font-size: 24px;
  color: #af103f;
  text-align: left;
}

.footer-subtitle {
  font-family: "Calibre";
  font-size: 21px;
  color: #ffffff;
  text-align: left;
}

.footer-link {
  color: #cae8e0 !important;
  font-family: "Calibre Bold" !important;
  font-size: 21px !important;
  text-decoration: none;
}

.form-group {
  display: inline-block;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.home {
  background: url(../assets/5.png) no-repeat center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  background-position: right top;
  background-attachment: fixed;
  margin: 0px, 140px, 0px, 140px !important;
}

.navbar img {
  /*Checar medida exacta*/
  max-height: 15vh;
  background-color: #af103f;
  padding: 30px 20px 20px 20px;
}

.navbar {
  padding-left: 50px;
  padding-top: 0px !important;
}

.card {
  border-radius: 0px !important;
  padding: 75px;
  margin-right: 5px !important;
  margin-left: 5px !important;
  height: 600px;
  width: 600px;
  text-align: left;
}

.cards-title {
  padding: 50px 75px 50px 75px !important;
}

.card-title {
  font-family: "Calibre Bold";
  font-size: 60px;
  color: #1A1818;
}

.card-text {
  font-family: "Epicene Text";
  font-size: 20px;
  color: #1A1818;
}

.cards-options li {
  font-family: "Calibre Bold";
  font-size: 22px;
  display: block;
  color: #1A1818;
}

.carousel-inner {
  align-content: center !important;
}

#materials {
  background-color: rgba(169, 211, 200, 0.8);
}

#production {
  background-color: rgba(242, 221, 161, 0.8);
}

#marketing {
  background-color: rgba(235, 179, 163, 0.8);
}

#regulatory {
  background-color: rgba(239, 193, 202, 0.8);
}

#deploy {
  background-color: rgba(161, 169, 214, 0.8);
}

.carousel-indicators button {
  width: 10px !important;
  height: 10px !important;
  border-radius: 100% !important;
}

.carousel-control-next, .carousel-control-prev {
    opacity: 0 !important;
    filter:alpha(opacity=0); /* IE support */
}

.footer {
  padding: 140px, 140px, 100px, 140px !important;
}

@media only screen and (max-width: 768px) {
  [class*="col-"] {
    width: 100%;
  }

  .navbar-text {
    display: none;
  }

  .navbar {
    align-items: center;
  }

  .title {
    font-size: 50px;
    text-align: center;
  }
  .subtitle,
  .subtitle2 {
    font-size: 20px;
    text-align: center;
  }
  .landing,
  .cards-title,
  .contact-form,
  .subtitle2,
  .footer {
    padding-right: 20px !important;
    padding-left: 20px !important;
    padding-top: 0px;
  }

  .landing {
    min-height: 80vh !important;
    margin-top: 35px !important;
  }

  .contact-form {
    min-height: 80vh !important;
  }

  .text-epi,
  .text-epi-bold {
    text-align: center;
    font-size: 15px;
  }

  .footer {
    padding-top: 0px !important;
    padding-bottom: 85px !important;
  }

  .footer-title,
  .footer-subtitle {
    text-align: center;
  }

  /*.home {
    text-align: center !important;
  }*/
}

@media only screen and (max-width: 834px) {
  [class*="col-"] {
    width: 100%;
  }

  .navbar {
    align-items: center;
  }
}

@media only screen and (max-width: 1920px) {
}
</style>
