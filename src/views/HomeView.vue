<script>
import Header from "../components/Header.vue";
import Contacts from "../components/Contacts.vue";
import Products from "../components/Products.vue";

export default {
  components: {Products, Contacts, Header}
}
</script>

<template>
  <Header/>
  <Contacts/>
  <Products/>
</template>
