<template>
  <!-- Masthead-->
  <header class="masthead">
    <div class="container">
      <div class="masthead-subheading">Bienvenidos a</div>
      <div class="masthead-heading text-uppercase">Saitama Developers</div>
      <a class="btn btn-primary btn-xl text-uppercase" href="#services"
        >Ver más</a
      >
    </div>
  </header>
  <!-- Services-->
  <section class="page-section" id="services">
    <div class="container">
      <div class="text-center">
        <h2 class="section-heading text-uppercase text-white">Servicios</h2>
        <h3 class="section-subheading text-muted">
          Los servicios que brindamos
        </h3>
      </div>
      <div class="row text-center">
        <div class="col-md-4 h-100">
          <span class="fa-stack fa-4x">
            <i class="fas fa-circle fa-stack-2x text-primary"></i>
            <i class="fas fa-shopping-cart fa-stack-1x fa-inverse"></i>
          </span>
          <h4 class="my-3 text-white">E-Commerce</h4>
          <p class="text-muted">
            Pagina web ecommerce, con sistemas de pagos, envios y tu propio
            panel de control.
          </p>
        </div>
        <div class="col-md-4 h-100">
          <span class="fa-stack fa-4x">
            <i class="fas fa-circle fa-stack-2x text-primary"></i>
            <i class="fas fa-code fa-stack-1x fa-inverse"></i>
          </span>
          <h4 class="my-3 text-white">Desarrollo Web</h4>
          <p class="text-muted">
            Desarrollo y diseño de sitios webs. Lenguajes de programación como
            Vuejs, PHP, Nodejs. Bases de datos Mysql, MongoDB.
          </p>
        </div>
        <div class="col-md-4 h-100">
          <span class="fa-stack fa-4x">
            <i class="fas fa-circle fa-stack-2x text-primary"></i>
            <i class="fas fa-lock fa-stack-1x fa-inverse"></i>
          </span>
          <h4 class="my-3 text-white">Testing</h4>
          <p class="text-muted">
            Realización de testing, para detectar fallas y/o vulnerabilidades de
            sitios web desarrollado en Vue.
          </p>
        </div>
      </div>
    </div>
  </section>
  <!-- Portfolio Grid-->
  <section class="page-section bg-light" id="portfolio">
    <div class="container">
      <div class="text-center">
        <h2 class="section-heading text-uppercase">Portafolio</h2>
        <h3 class="section-subheading text-muted">
          Mira nuestros proyectos más destacados
        </h3>
      </div>
      <div class="row">
        <div class="col-lg-4 col-sm-6 mb-4">
          <!-- Portfolio item 1-->
          <div class="portfolio-item">
            <a
              class="portfolio-link"
              data-bs-toggle="modal"
              href="#portfolioModal1"
            >
              <div class="portfolio-hover">
                <div class="portfolio-hover-content">
                  <i class="fas fa-plus fa-3x"></i>
                </div>
              </div>
              <img class="img-fluid" src="img/Screenshot_1.png" alt="..." />
            </a>
            <div class="portfolio-caption">
              <div class="portfolio-caption-heading">Estudio Pinardi</div>
              <div class="portfolio-caption-subheading text-muted">
                Desarrollo Web
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-sm-6 mb-4">
          <!-- Portfolio item 2-->
          <div class="portfolio-item">
            <a
              class="portfolio-link"
              data-bs-toggle="modal"
              href="#portfolioModal2"
            >
              <div class="portfolio-hover">
                <div class="portfolio-hover-content">
                  <i class="fas fa-plus fa-3x"></i>
                </div>
              </div>
              <img class="img-fluid" src="img/Screenshot_2.png" alt="..." />
            </a>
            <div class="portfolio-caption">
              <div class="portfolio-caption-heading">Transporte Piro</div>
              <div class="portfolio-caption-subheading text-muted">
                Desarrollo Web
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-sm-6 mb-4">
          <!-- Portfolio item 3-->
          <div class="portfolio-item">
            <a
              class="portfolio-link"
              data-bs-toggle="modal"
              href="#portfolioModal3"
            >
              <div class="portfolio-hover">
                <div class="portfolio-hover-content">
                  <i class="fas fa-plus fa-3x"></i>
                </div>
              </div>
              <img class="img-fluid" src="img/Screenshot_3.png" alt="..." />
            </a>
            <div class="portfolio-caption">
              <div class="portfolio-caption-heading">Tus compras online</div>
              <div class="portfolio-caption-subheading text-muted">
                E-commerce
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- About-->
  <section class="page-section" id="about">
    <div class="container">
      <div class="text-center">
        <h2 class="section-heading text-uppercase text-white">
          Sobre nosotros
        </h2>
        <h3 class="section-subheading text-muted">
          Somos un equipo de desarrolladores web, freelance, con más de 5 años
          de experiencia. <br />
          Te contamos nuestra forma de trabajar:
          <i class="fas fa-arrow-down"></i>
        </h3>
      </div>
      <ul class="timeline">
        <li>
          <div class="timeline-image">
            <img
              class="rounded-circle img-fluid"
              src="assets/img/about/1.jpg"
              alt="..."
            />
          </div>
          <div class="timeline-panel">
            <div class="timeline-heading">
              <h4 class="subheading">Maquetación y funcionalidad</h4>
            </div>
            <div class="timeline-body">
              <p class="text-muted">
                Al principio se realiza la maquetación del sitio web, definiendo
                el diseño y las funcionalidades de la misma, tanto de lado del
                cliente como del servidor.
              </p>
            </div>
          </div>
        </li>
        <li class="timeline-inverted">
          <div class="timeline-image">
            <img
              class="rounded-circle img-fluid"
              src="assets/img/about/2.jpg"
              alt="..."
            />
          </div>
          <div class="timeline-panel">
            <div class="timeline-heading">
              <!-- <h4>March 2011</h4> -->
              <h4 class="subheading">Realización del diseño/Frontend</h4>
            </div>
            <div class="timeline-body">
              <p class="text-muted">
                Luego se desarrolla el diseño del todo el sitio web con código,
                es decir todo el frontend y sus funcionalidades
              </p>
            </div>
          </div>
        </li>
        <li>
          <div class="timeline-image">
            <img
              class="rounded-circle img-fluid"
              src="assets/img/about/3.jpg"
              alt="..."
            />
          </div>
          <div class="timeline-panel">
            <div class="timeline-heading">
              <!-- <h4>December 2015</h4> -->
              <h4 class="subheading">CMS/Backend</h4>
            </div>
            <div class="timeline-body">
              <p class="text-muted">
                Despues se realiza el backend, o sea el lado del servidor,
                funcionalidades CRUD, seguridad. Creación del CMS y base de
                datos.
              </p>
            </div>
          </div>
        </li>
        <li class="timeline-inverted">
          <div class="timeline-image">
            <img
              class="rounded-circle img-fluid"
              src="assets/img/about/4.jpg"
              alt="..."
            />
          </div>
          <div class="timeline-panel">
            <div class="timeline-heading">
              <!-- <h4>July 2020</h4> -->
              <h4 class="subheading">Sitio listo en la web</h4>
            </div>
            <div class="timeline-body">
              <p class="text-muted">
                Y finalmente se detecta vulnerabilidades o errores. Una vez que
                todo el sitio este en orden, se sube a la web con su respectivo
                dominio.
              </p>
            </div>
          </div>
        </li>
        <li class="timeline-inverted">
          <div class="timeline-image">
            <h4>
              ¡Felicidades
              <br />
              tu sitio está
              <br />
              en la Web!
            </h4>
          </div>
        </li>
      </ul>
    </div>
  </section>
  <!-- Team-->
  <!-- <section class="page-section bg-light" id="team">
    <div class="container">
      <div class="text-center">
        <h2 class="section-heading text-uppercase">Our Amazing Team</h2>
        <h3 class="section-subheading text-muted">
          Lorem ipsum dolor sit amet consectetur.
        </h3>
      </div>
      <div class="row">
        <div class="col-lg-4">
          <div class="team-member">
            <img
              class="mx-auto rounded-circle"
              src="assets/img/team/1.jpg"
              alt="..."
            />
            <h4>Parveen Anand</h4>
            <p class="text-muted">Lead Designer</p>
            <a class="btn btn-dark btn-social mx-2" href="#!"
              ><i class="fab fa-twitter"></i
            ></a>
            <a class="btn btn-dark btn-social mx-2" href="#!"
              ><i class="fab fa-facebook-f"></i
            ></a>
            <a class="btn btn-dark btn-social mx-2" href="#!"
              ><i class="fab fa-linkedin-in"></i
            ></a>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="team-member">
            <img
              class="mx-auto rounded-circle"
              src="assets/img/team/2.jpg"
              alt="..."
            />
            <h4>Diana Petersen</h4>
            <p class="text-muted">Lead Marketer</p>
            <a class="btn btn-dark btn-social mx-2" href="#!"
              ><i class="fab fa-twitter"></i
            ></a>
            <a class="btn btn-dark btn-social mx-2" href="#!"
              ><i class="fab fa-facebook-f"></i
            ></a>
            <a class="btn btn-dark btn-social mx-2" href="#!"
              ><i class="fab fa-linkedin-in"></i
            ></a>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="team-member">
            <img
              class="mx-auto rounded-circle"
              src="assets/img/team/3.jpg"
              alt="..."
            />
            <h4>Larry Parker</h4>
            <p class="text-muted">Lead Developer</p>
            <a class="btn btn-dark btn-social mx-2" href="#!"
              ><i class="fab fa-twitter"></i
            ></a>
            <a class="btn btn-dark btn-social mx-2" href="#!"
              ><i class="fab fa-facebook-f"></i
            ></a>
            <a class="btn btn-dark btn-social mx-2" href="#!"
              ><i class="fab fa-linkedin-in"></i
            ></a>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-8 mx-auto text-center">
          <p class="large text-muted">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut eaque,
            laboriosam veritatis, quos non quis ad perspiciatis, totam corporis
            ea, alias ut unde.
          </p>
        </div>
      </div>
    </div>
  </section> -->
  <!-- Clients-->
  <div class="py-5 clientes">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-4 col-sm-6 my-3">
          <a href="#!"
            ><img
              class="img-fluid img-brand d-block mx-auto logo"
              src="img/logo-pinardi.png"
              alt="Estudio Pinardi"
          /></a>
        </div>
        <div class="col-md-4 col-sm-6 my-3">
          <a href="#!"
            ><img
              class="img-fluid img-brand d-block mx-auto logo"
              src="img/logo-piro.png"
              alt="Transporte Piro"
          /></a>
        </div>
        <div class="col-md-4 col-sm-6 my-3">
          <a href="#!"
            ><img
              class="img-fluid img-brand d-block mx-auto logo"
              src="img/logo-tuscompras.png"
              alt="Tus compras online"
          /></a>
        </div>
        <!-- <div class="col-md-3 col-sm-6 my-3">
          <a href="#!"
            ><img
              class="img-fluid img-brand d-block mx-auto"
              src="assets/img/logos/ibm.svg"
              alt="..."
          /></a>
        </div> -->
      </div>
    </div>
  </div>
  <!-- Contact-->
  <section class="page-section" id="contact">
    <div class="container">
      <div class="text-center">
        <h2 class="section-heading text-uppercase">Contáctanos</h2>
        <h3 class="section-subheading text-muted">
          Estamos de Lunes a Sabados de 09 a 20hs
        </h3>
      </div>
      <!-- * * * * * * * * * * * * * * *-->
      <!-- * * SB Forms Contact Form * *-->
      <!-- * * * * * * * * * * * * * * *-->
      <!-- This form is pre-integrated with SB Forms.-->
      <!-- To make this form functional, sign up at-->
      <!-- https://startbootstrap.com/solution/contact-forms-->
      <!-- to get an API token!-->
      <form id="contactForm" @submit.prevent="enviar">
        <div class="row align-items-stretch mb-5">
          <div class="col-md-6">
            <div class="form-group">
              <!-- Name input-->
              <input
                class="form-control"
                type="text"
                placeholder="Nombre completo *"
                v-model="formData.nombre"
                :class="{ error: formError.nombre }"
              />
            </div>
            <div class="form-group">
              <!-- Email address input-->
              <input
                class="form-control"
                id="email"
                type="email"
                placeholder="Correo electrónico *"
                v-model="formData.email"
                :class="{ error: formError.email }"
              />
            </div>
            <div class="form-group mb-md-0">
              <!-- Phone number input-->
              <input
                class="form-control"
                id="phone"
                type="tel"
                placeholder="Teléfono *"
                v-model="formData.tel"
                :class="{ error: formError.tel }"
              />
            </div>
          </div>
          <div class="col-md-6">
            <div class="form-group form-group-textarea mb-md-0">
              <!-- Message input-->
              <textarea
                class="form-control"
                id="message"
                placeholder="Escribe tu mensaje *"
                v-model="formData.mensaje"
                :class="{ error: formError.mensaje }"
              ></textarea>
            </div>
          </div>
        </div>
        <div
          class="alert alert-success alert-dismissible fade show"
          role="alert"
          v-if="enviado"
        >
          <strong>¡Mensaje enviado!</strong> Estaremos en contacto con usted.
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="alert"
            aria-label="Close"
          ></button>
        </div>
        <div
          class="alert alert-warning alert-dismissible fade show"
          role="alert"
          v-if="no_enviado"
        >
          <strong>¡Mensaje no enviado!</strong> Complete los datos requeridos*.
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="alert"
            aria-label="Close"
          ></button>
        </div>
        <!-- Submit success message-->
        <!---->
        <!-- This is what your users will see when the form-->
        <!-- has successfully submitted-->

        <!-- Submit error message-->
        <!---->
        <!-- This is what your users will see when there is-->
        <!-- an error submitting the form-->

        <!-- Submit Button-->
        <div class="text-center">
          <button
            class="btn btn-primary btn-xl text-uppercase"
            id="submitButton"
            type="submit"
          >
            Enviar Mensaje
          </button>
        </div>
      </form>
    </div>
  </section>
</template>

<script>
import { ref } from "vue";
import * as Yup from "yup";
import emailjs from "@emailjs/browser";


export default {
  setup() {
    const formData = ref({});
    const formError = ref({});
    const enviado = ref(false);
    const no_enviado = ref(false);

    const schemaForm = Yup.object().shape({
      nombre: Yup.string().required(true),
      tel: Yup.string().required(true),
      email: Yup.string().email(true).required(true),
      mensaje: Yup.string().required(true),
    });

    const enviar = async () => {
      formError.value = {};

      try {
        await schemaForm.validate(formData.value, { abortEarly: false });

        try {
      
          var templateParams = {
            nombre: formData.value.nombre,
            email: formData.value.email,
            tel: formData.value.tel,
            mensaje: formData.value.mensaje,
          };

          emailjs
            .send(
              "service_7izq809",
              "template_hdba90r",
              templateParams,
              "user_RN5CSsGwVbYzb8oAEaXQf"
            )
            .then(
              (result) => {
                console.log("SUCCESS!", result.status, result.text);
              },
              (error) => {
                console.log("FAILED...", error);
              }
            );

   
          enviado.value = true;
          no_enviado.value = false;

          formData.value = "";
        } catch (error) {
          console.log(error);
        }
      } catch (error) {
        error.inner.forEach((err) => {
          formError.value[err.path] = err.message;
        });

        no_enviado.value = true;
        enviado.value = false;
      }
    };

    return {
      formData,
      enviar,
      formError,
      enviado,
      no_enviado,
    };
  },
};
</script>

<style scoped>
.logo {
  width: 35%;
}

input.error {
  border: 2px solid rgb(252, 41, 41) !important;
  background-color: #f7e5e5 !important;
}

textarea.error {
  border: 2px solid rgb(252, 41, 41) !important;
  background-color: #f7e5e5 !important;
}
</style>
