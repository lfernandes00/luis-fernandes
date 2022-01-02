<template>
  <div>
  <b-navbar id="nav" class="navbar-menu has-background-one" >
    <b-navbar-nav id="navItems">
      <b-nav-item href="#">About Me</b-nav-item>

      <b-nav-item href="#">Skills</b-nav-item>

      <b-nav-item href="#">Projects</b-nav-item>
    </b-navbar-nav>
  </b-navbar>
</div>
</template>

<script>
export default {
name:"NavBar"
}
</script>

<style>
#nav {
    min-height: 3.25rem;
    background-image: linear-gradient(to bottom right, rgb(2, 2, 100), rgb(22, 22, 99));
    color: white!important;
}
#navItems {
    margin-left: 3.9rem;
    margin-right: 3.9rem;
}

</style>