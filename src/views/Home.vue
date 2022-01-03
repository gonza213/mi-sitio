<template>
  <div class="home">
     <Nav />
     <Inicio />
     <Footer />
     <Modal />
  </div>
</template>

<script>
import Nav from '../components/Nav.vue'
import Inicio from '../components/Inicio.vue'
import Footer from '../components/Footer.vue'
import Modal from '../components/Modal.vue'

export default {
  name: 'Home',
  components: {
    Nav, 
    Inicio, 
    Footer,
    Modal
  }
}
</script>
