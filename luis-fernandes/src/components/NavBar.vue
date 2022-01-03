<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-toggle id="toggle" target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="#">About Me</b-nav-item>
          <b-nav-item href="#">Skills</b-nav-item>
          <b-nav-item href="#">Projects</b-nav-item>
        </b-navbar-nav>
        <b-navbar-nav id="navRight">
          <b-button id="talkBtn" type="submit">Talk to me</b-button>
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
    to bottom right,
    rgb(20, 30, 117),
    rgb(64, 81, 231)
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
  color: black !important;
}
#navRight {
  margin-left: auto;
}
#talkBtn {
  color: white;
  background-color: rgb(29, 33, 68);
  border: none;
}
</style>