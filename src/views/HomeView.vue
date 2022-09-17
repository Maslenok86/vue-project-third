<script>
import Header from "../components/Header.vue";
import Contacts from "../components/Contacts.vue";
import Products from "../components/Products.vue";
import Projects from "../components/Projects.vue";
import Culture from "../components/Culture.vue";
import Facts from "../components/Facts.vue";
import Footer from "../components/Footer.vue";

export default {
  components: {Footer, Facts, Culture, Projects, Products, Contacts, Header}
}
</script>

<template>
  <Header/>
  <Contacts/>
  <Products/>
  <Projects/>
  <Culture/>
  <Facts/>
  <Footer/>
</template>
