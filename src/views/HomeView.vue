<script>
import Header from "../components/Header.vue";
import Contacts from "../components/Contacts.vue";
import Products from "../components/Products.vue";
import Projects from "../components/Projects.vue";

export default {
  components: {Projects, Products, Contacts, Header}
}
</script>

<template>
  <Header/>
  <Contacts/>
  <Products/>
  <Projects/>
</template>
