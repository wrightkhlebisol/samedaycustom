<template>
  <b-col cols="2" class="leftnav">
    <b-nav vertical>
      <b-nav-item>X</b-nav-item>
      <b-dropdown-divider></b-dropdown-divider>
      <b-nav-item active>Dashboard</b-nav-item>
      <b-nav-item>Operations</b-nav-item>
      <div class="customdropdown">
        <b-dropdown-item>Orders</b-dropdown-item>
        <b-dropdown-item>Production House</b-dropdown-item>
        <b-dropdown-item>Bids</b-dropdown-item>
        <b-dropdown-item>Promotion / Discount</b-dropdown-item>
        <b-dropdown-item>Out Sourcing</b-dropdown-item>
      </div>
      <b-nav-item>Records</b-nav-item>
      <b-nav-item>Supply Store</b-nav-item>
      <b-nav-item>Market Place</b-nav-item>
      <b-nav-item>Forums</b-nav-item>
      <b-nav-item>Settings</b-nav-item>
    </b-nav>
  </b-col>
</template>

<script>
export default {}
</script>

<style scoped>
.leftnav {
  background-color: blue;
  box-sizing: border-box;
  padding-right: 0;
}
</style>