<template>
  <Navbar />
  <Header></Header>
  <Info />
  <About />
  <Customers />
  <Footer></Footer>
</template>

<script>
import Navbar from './Navbar.vue'
import Header from './Header.vue'
import Info from './Info.vue';
import Footer from './Footer.vue';
import Customers from './Customers.vue';
import About from './About.vue';
export default {
  components: { Navbar, Header, Info, Footer,Customers, About },

}
</script>

<style>

</style>