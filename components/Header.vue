<template>
  <div id="header" class="text-center">
    <b-navbar toggleable="lg" type="dark">
      <b-navbar-brand href="#"><img src="~/assets/images/logo_white.png"></b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#aboutme">About us</b-nav-item>
          <b-nav-item href="#experience">Experience</b-nav-item>
          <b-nav-item href="#services">Services</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<style>
#header {
  background: #000;
  position: fixed;
  z-index: 99;
  width: 100%;
  padding: 0.5rem;
}

#header ul li a {
  color: #fff;
}

.navbar-brand img {
  max-width: 50px;
}

.navbar-light .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 32 32' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255,102,203, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 8h24M4 16h24M4 24h24'/%3E%3C/svg%3E");
}

</style>
