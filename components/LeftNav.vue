<template>
  <b-col cols="2" class="leftnav">
    <div class="togglenav">X</div>
    <b-nav vertical>
      <b-nav-item active>Dashboard</b-nav-item>
      <b-nav-item>
        Operations
        <div class="customdropdown">
          <b-dropdown-item class="dropItem">Orders</b-dropdown-item>
          <b-dropdown-item class="dropItem">Production House</b-dropdown-item>
          <b-dropdown-item class="dropItem">Bids</b-dropdown-item>
          <b-dropdown-item class="dropItem">Promotion / Discount</b-dropdown-item>
          <b-dropdown-item class="dropItem">Out Sourcing</b-dropdown-item>
        </div>
      </b-nav-item>
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
.dropItem {
  color: #fff;
  font-size: 15px;
  text-align: left;
  letter-spacing: 1.5px;
  opacity: 1;
}

.dropdown-item {
  display: block;
  width: 100%;
  padding: 0.65rem 0;
}
.leftnav {
  background-color: #007afe;
  box-sizing: border-box;
  padding-right: 0;
  padding-left: 10px;
  font-size: 15px;
  text-align: left;
  letter-spacing: 1.5px;
  opacity: 1;
}

.togglenav {
  padding: 30px 30px 30px 0;
  color: #fff;
  border-bottom: 1px solid #2268d8;
}

li.nav-item {
  border-bottom: 1px solid #2268d8;
}

.leftnav a {
  color: #fff;
  padding: 20px 20px 20px 0;
}

.dropdown-divider {
  height: 1px;
}
</style>