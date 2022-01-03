<template>
  <div>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
    <div class="navbar-nav">
      <a class="nav-item nav-link" href="#">About Me</a>
      <a class="nav-item nav-link" href="#">Skills</a>
      <a class="nav-item nav-link" href="#">Projects</a>
    </div>
  </div>
</nav>
</div>
</template>

<script>
export default {
name:"NavBar"
}
</script>

<style>
nav {
    min-height: 3.25rem;
    background-image: linear-gradient(to bottom right, rgb(20, 30, 117), rgb(64, 81, 231));
}
#navbarNavAltMarkup {
    margin-left: 3.9rem;
    margin-right: 3.9rem;
}
nav .navbar-nav .nav-item {
  color: white !important;
  font-weight: bold;
}
.nav-item.nav-item.nav-item a:hover {
  color: black
}

</style>