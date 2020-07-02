<template>
  <div id="app">
    <b-jumbotron
      id="content1"
      bg-variant="secondary"
      text-variant="light"
      header-level="4"
    >
      <template slot="header">謝時銘</template>
      <template slot="lead">
        私はソフトウェア開発に情熱を注いでおり、プログラミングの効率と品質を向上させるために、余暇に読書や実験をすることで自分のスキルを豊かにしています。
      </template>
      <hr style="background-color: #282828" />
      <p>
        このページは作品集です
      </p>
      <div align="center">
        <b-button variant="primary" href="https://github.com/bevis00/Resume"
          >Profile</b-button
        >
        <b-button id="mailbtn" variant="success">E-mail</b-button>
        <b-popover target="mailbtn" placement="bottom">
          shihming.hsieh@gmail.com
        </b-popover>
      </div>
    </b-jumbotron>

    <b-jumbotron id="content2" header="Works List" header-level="4">
      <b-container fluid class="p-4 bg-dark">
        <b-row>
          <b-col>
            <b-modal centered hide-footer hide-header v-model="show" size="lg">
              <iframe
                width="100%"
                height="480"
                src="https://www.youtube.com/embed/duDXEQRgYRs"
                frameborder="0"
                allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen
              ></iframe>
              <b-button variant="outline-danger" block v-on:click="show = false"
                >Close</b-button
              >
            </b-modal>
            <b-carousel
              style="text-shadow: 0px 0px 2px #000"
              v-model="slide"
              v-on:sliding-start="onSlideStart"
              fade
              controls
              indicators
            >
              <b-carousel-slide img-src="img/Tron.jpg">
                <b-button variant="outline-light" v-on:click="show = true"
                  >video</b-button
                >
                <h1 style="color: #ffffff">Tron 立方射擊遊戲</h1>
              </b-carousel-slide>
              <b-carousel-slide img-src="img/GameProgramming.jpg">
                <h1 style="color: #ffffff">Game Programming</h1>
              </b-carousel-slide>
              <b-carousel-slide img-src="img/Web3D.jpg">
                <h1 style="color: #000000">Web 3D</h1>
              </b-carousel-slide>
              <b-carousel-slide img-src="img/ComputerGraphics.jpg">
                <h1 style="color: #000000">Computer Graphics</h1>
              </b-carousel-slide>
            </b-carousel>
          </b-col>
        </b-row> </b-container
      ><br /><br />
      <div align="center">
        <b-button variant="primary" v-bind:href="link">Link</b-button>
      </div>
    </b-jumbotron>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      slide: 0,
      show: false,
      link: "https://ojrock.github.io/tron/tron.html",
    };
  },
  methods: {
    onSlideStart(slide) {
      switch (slide) {
        case 0:
          this.link = "https://ojrock.github.io/tron/tron.html";
          break;
        case 1:
          this.link = "https://bevis00.github.io/ex/index.html";
          break;
        case 2:
          this.link = "https://bevis00.github.io/w3d/index.html";
          break;
        case 3:
          this.link = "https://bevis00.github.io/ComputerGraphics/index.html";
      }
    },
  },
};
</script>

<style lang="scss">
#app {
  display: flex;
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#content1 {
  flex: 0 2 auto;
  margin-bottom: 0;
  max-width: 50vw;
  max-height: 100vh;
}

#content1 .display-4 {
  margin-bottom: 3rem;
}

#content1 hr {
  margin-top: 3rem !important;
  margin-bottom: 3rem !important;
}

#content1 p {
  margin-bottom: 5rem !important;
}

#content2 {
  flex: 0 1 auto;
  margin-bottom: 0;
  width: 100vw;
  height: 100vh;
}

@media (max-width: 768px) {
  #app {
    flex-direction: column;
  }

  #content1 {
    max-width: 100vw;
  }

  #content1 hr {
    margin-top: 1.5rem !important;
    margin-bottom: 1.5rem !important;
  }

  #content1 p {
    margin-bottom: 1rem !important;
  }

  #content2 {
    height: 100%;
  }

  .carousel-caption h1 {
    font-size: 5vw;
  }
}
</style>
