<template>
  <b-row align-v="start" class="shadow p-3 mb-5 bg-white rounded">
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-col cols="5">
        <b-navbar-brand href="#">
          <img src="/desktoplogooptimized.svg" />
        </b-navbar-brand>
      </b-col>
      <b-col cols="2">Search</b-col>
      <b-col cols="1">Message</b-col>
      <b-col cols="2">Market Place</b-col>
      <b-col cols="1">Notifications</b-col>
      <b-col cols="1">Me</b-col>
    </b-navbar>
  </b-row>
</template>

<script>
export default {}
</script>

<style scoped>
nav.navbar.navbar-dark.bg-info.navbar-expand-lg {
  width: 100%;
  background-color: #fff !important;
  color: #000 !important;
}
.navbar-brand {
  height: 50px;
}

.navbar-brand img {
  height: 100%;
}
</style>