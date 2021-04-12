<template>
  <q-page class="flex flex-center">
    <Navbar />
    <div id="articles" class="articles q-pa-md row items-start justify-center q-gutter-md col-md-9">
    <Card />
    <Card />
    <Card />
    <Card />
    </div > 
    <Footer />
  </q-page>
</template>

<script>
import Navbar from "../components/Navbar.vue";
import Card from "../components/Card.vue";
import Footer from "../components/Footer.vue";

export default {
  name: 'PageIndex',
  components: {
    Navbar,
    Card,
    Footer
  }
}
</script>
