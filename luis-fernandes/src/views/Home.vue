<template>
  <div class="home">
    <section id="landingPage">
      <div class="container">
        <div id="landingRow" class="row align-items-center">
          <div class="col-lg-6">
            <h1 id="nameTitle" class="text-center">Luís Fernandes</h1>
            <h3 id="title" class="text-center">Web Developer</h3>
          </div>
        </div>
      </div>
    </section>
    <section id="aboutPage">
      <div class="container">
        <div id="aboutTitle">
          <h1 class="text-center">About Me</h1>
        </div>
        <div id="bioRow" class="row align-items-center">
          <div class="col-lg-4 text-center">
            <img src="../assets/foto.jpg" id="photo" /><br />
            <a
              id="linkedinIcon"
              href="https://www.linkedin.com/in/lu%C3%ADs-fernandes-929712223/"
              target="_blank"
              ><b-icon class="mt-3" icon="linkedin"></b-icon
            ></a>
            <a
              id="gitIcon"
              href="https://github.com/lfernandes00"
              target="_blank"
              ><b-icon icon="github"></b-icon
            ></a>
          </div>
          <div id="bioText" class="col-lg-8">
            I’m a 21 year old student at Escola Superior de Media Artes e Design
            - IPP, currently in the 3rd year of the Degree at Web Information
            Systems and Technologies. I consider myself very ambitious,
            hardworking and I’m always ready to learn new skills that will
            improve my career and my personal life.
          </div>
        </div>
      </div>
    </section>
    <section id="projectPage">
      <div class="container">
        <h1 id="projectTitle" class="text-center">My Projects</h1>
        <div class="row">
          <div class="col-lg-4 f-flex justify-content-center">
            <b-card
              title="Trivia Owl"
              img-src="https://picsum.photos/600/300/?image=25"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 25rem"
              class="mb-2 shadow bg-white rounded"
            >
              <b-card-text>
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </b-card-text>

              <b-button id="cardBtn" href="#" >Poster</b-button>
              <b-button id="cardBtn" href="#" >GitHub</b-button>
            </b-card>
          </div>

          <div class="col-lg-4 f-flex justify-content-center">
            <b-card
              title="Trivia-OwlAPI"
              img-src="https://picsum.photos/600/300/?image=25"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 25rem"
              class="mb-2 shadow bg-white rounded"
            >
              <b-card-text>
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </b-card-text>

              <b-button href="#" variant="primary">Poster</b-button>
              <b-button href="#" variant="primary">GitHub</b-button>
            </b-card>
          </div>

          <div class="col-lg-4 f-flex justify-content-center">
            <b-card
              title="Pang Game"
              img-src="https://picsum.photos/600/300/?image=25"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 25rem"
              class="mb-2 shadow bg-white rounded"
            >
              <b-card-text>
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </b-card-text>

              <b-button href="#" variant="primary">Poster</b-button>
              <b-button href="#" variant="primary">GitHub</b-button>
            </b-card>
          </div>

          <div class="col-lg-4 f-flex justify-content-center">
            <b-card
              title="Docflow"
              img-src="https://picsum.photos/600/300/?image=25"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 25rem;"
              class="mb-2 shadow bg-white rounded"
            >
              <b-card-text>
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </b-card-text>

              <b-button href="#" variant="primary">Poster</b-button>
              <b-button href="#" variant="primary">GitHub</b-button>
            </b-card>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>

<style>
#landingPage {
  background-color: white;
  height: 100vh;
}
#nameTitle {
  color: black;
  text-transform: uppercase;
  font-weight: bold;
}
#landingRow {
  min-height: 100vh;
}
#aboutPage {
  background-color: rgb(47, 50, 80);
  min-height: 80vh;
}
#photo {
  width: 250px;
  border-radius: 20px 20px 20px 20px;
}
#bioText {
  color: white;
  max-width: 750px;
  text-align: justify;
  line-height: 25px;
}
#gitIcon {
  color: rgb(46, 175, 207) !important;
  text-decoration: none;
}
#linkedinIcon {
  color: rgb(46, 175, 207) !important;
  text-decoration: none;
}
#projectPage {
  background-color: white;
  height: 100vh;
}
#aboutTitle h1 {
  color: white;
  font-weight: bold;
  text-transform: uppercase;
  padding-top: 50px;
  padding-bottom: 50px;
}
#projectTitle {
  color: Black;
  font-weight: bold;
  text-transform: uppercase;
  padding-top: 50px;
  padding-bottom: 50px;
}
#cardBtn {
  background-color: rgb(47, 50, 80);
}
</style>