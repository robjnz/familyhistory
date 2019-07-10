<template>
<section nav class="nav-bar">
  <b-navbar toggleable="md" type="dark" variant="info">


  <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

  <img src="/logo_transparent.png" height="50" width="50" class="d-inline-block align-top" alt="LondonEast logo">


  <b-navbar-brand href="/" class="title">Family History</b-navbar-brand>

  <b-collapse is-nav id="nav_collapse">

    <b-navbar-nav class="nav">
      <b-nav-item href="/">Home</b-nav-item>
      <b-nav-item href="/australasia">Australasia</b-nav-item>
      <b-nav-item href="/uk">uk</b-nav-item>

      <b-nav-item-dropdown text="Europe" right>
        <b-dropdown-item href="/belarus">Belarus</b-dropdown-item>


      </b-nav-item-dropdown>

      <b-nav-item-dropdown text="Jewish" right>
        <b-dropdown-item href="/shoah">Shoah</b-dropdown-item>
        <b-dropdown-item href="/australasia/jewish">Australasia</b-dropdown-item>
        <b-dropdown-item href="/belarus/jewish">Belarus</b-dropdown-item>
        <b-dropdown-item href="/uk/jewish">Uk</b-dropdown-item>

      </b-nav-item-dropdown>

    </b-navbar-nav>

    <!-- Right aligned nav items -->
    <b-navbar-nav class="ml-auto">
    </b-navbar-nav>

  </b-collapse>
</b-navbar>
</section>

</template>

<style scoped>



.title{
  color    : gold;
  font-size: 1.5rem;

}

.nav{
  font-size: 21px;

}

.dropdown-item{
background: #343A40;
color     : whitesmoke;
}

a:hover {
  color: gold;
}

a:hover {
  text-decoration: none;
}

a:visited {
  color: gold;
}

</style>
