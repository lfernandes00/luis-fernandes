<template>
  <div>
    <b-navbar class="fixed-top" toggleable="lg" type="dark" variant="info">
      <b-navbar-toggle id="toggle" target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="#">About Me</b-nav-item>
          <b-nav-item href="#">Skills</b-nav-item>
          <b-nav-item href="#">Projects</b-nav-item>
        </b-navbar-nav>
        <b-navbar-nav id="navRight">
          <b-button id="cvBtn" href="./assets/CV.pdf" target="_blank" type="submit">CV</b-button>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style>
nav {
  min-height: 3.25rem;
  background-image: linear-gradient(
    to bottom ,
    rgb(46, 175, 207),
    rgb(27, 167, 202)
    
  );
}
#toggle {
  margin-left: 1.5rem;
}
#nav-collapse {
  margin-left: 6.9rem;
  margin-right: 6.9rem;
  background-image: white;
}
nav .navbar-nav .nav-item a {
  color: white !important;
  font-weight: bold;
}
nav .navbar-nav .nav-item a:hover {
  color: rgb(47, 50, 80) !important;
}
#navRight {
  margin-left: auto;
}
#cvBtn {
  color: white;
  background-color: rgb(47, 50, 80);
  border: none;
}
</style>