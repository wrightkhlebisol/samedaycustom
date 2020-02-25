<template>
  <b-container fluid class="bv-example-row">
    <b-row>
      <LeftNav></LeftNav>
      <b-col cols="10">
        <Header></Header>
        <Footer></Footer>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
import Header from '~/components/Header.vue'
import LeftNav from '~/components/LeftNav.vue'
import Footer from '~/components/Footer.vue'
export default {
  components: {
    Header,
    LeftNav,
    Footer
  }
}
</script>

<style>
</style>
