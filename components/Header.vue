<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="light">
      <b-navbar-brand href="#" class="text-dark">
        NavBar
      </b-navbar-brand>

      <b-navbar-toggle class="text-dark" target="nav-collapse" />

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#">
            Find property
          </b-nav-item>
          <b-nav-item href="#">
            Why Alterstay
          </b-nav-item>
          <b-nav-item href="#">
            Be an Alterstay
          </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<style>
.navbar-dark .navbar-nav .nav-link{
color:black!important
    }

    .navbar-dark .navbar-toggler-icon{
        filter: invert(1);
    }
</style>
