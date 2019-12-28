<template>
<section nav class="nav-bar">
  <b-navbar toggleable="md" type="dark" variant="info">


  <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

  <img src="/globe.jpg" height="40" width="40" class="d-inline-block align-top" alt="LondonEast logo">


  <b-navbar-brand href="/" class="title">Family History</b-navbar-brand>

  <b-collapse is-nav id="nav_collapse">

    <b-navbar-nav class="nav">
      <b-nav-item href="/">Home</b-nav-item>
      <b-nav-item href="/general">General</b-nav-item>
      <b-nav-item href="/australasia">Australasia</b-nav-item>
      <b-nav-item href="/canada">Canada</b-nav-item>
      <b-nav-item href="/Caribbean">Caribbean</b-nav-item>

      <b-nav-item-dropdown text="Europe" right>
        <b-dropdown-item href="/austria">Austria</b-dropdown-item>
        <b-dropdown-item href="/belarus">Belarus</b-dropdown-item>
        <b-dropdown-item href="/belgium">Belgium</b-dropdown-item>
        <b-dropdown-item href="/dutch">Dutch</b-dropdown-item>
        <b-dropdown-item href="/irish">Ireland</b-dropdown-item>
        <b-dropdown-item href="/russian">Russian</b-dropdown-item>
        <b-dropdown-item href="/ukraine">Ukraine</b-dropdown-item>

      </b-nav-item-dropdown>
      <b-nav-item href="/uk">UK</b-nav-item>
      <b-nav-item href="/usa">USA</b-nav-item>

      <b-nav-item-dropdown text="Jewish" right>
        <b-dropdown-item href="/jewish/general">General</b-dropdown-item>
        <b-dropdown-item href="/shoah">Shoah</b-dropdown-item>
        <b-dropdown-item href="/australasia/jewish">Australasia</b-dropdown-item>
        <b-dropdown-item href="/austria/jewish">Austria</b-dropdown-item>
        <b-dropdown-item href="/belarus/jewish">Belarus</b-dropdown-item>
        <b-dropdown-item href="/belgium/jewish">Belgium</b-dropdown-item>
        <b-dropdown-item href="/canada/jewish">Canada</b-dropdown-item>
        <b-dropdown-item href="/caribbean/jewish">Caribbean</b-dropdown-item>
        <b-dropdown-item href="/dutch/jewish">Dutch</b-dropdown-item>
        <b-dropdown-item href="/irish/jewish">Ireland</b-dropdown-item>
        <b-dropdown-item href="/russian/jewish">Russian</b-dropdown-item>
        <b-dropdown-item href="/uk/jewish">Uk</b-dropdown-item>
        <b-dropdown-item href="/ukraine/jewish">Ukraine</b-dropdown-item>
        <b-dropdown-item href="/usa/jewish">USA</b-dropdown-item>


      </b-nav-item-dropdown>
      <b-nav-item href="/contact">Contact</b-nav-item>
      <b-nav-item href="/login">Family History</b-nav-item>

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
