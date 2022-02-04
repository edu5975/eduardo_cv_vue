<template>
  <Header/>
  <Information/>
  <Footer/>
</template>

<script>

import Header from "./components/Header";
import Information from "./components/Information";
import Footer from "./components/Footer";
export default {
  name: 'App',
  components: {
    Footer,
    Information,
    Header
  }
}
</script>

<style>

</style>
