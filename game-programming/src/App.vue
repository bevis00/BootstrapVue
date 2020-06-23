<template>
  <div id="app">
    <b-jumbotron
      id="content1"
      bg-variant="secondary"
      text-variant="light"
      header-level="4"
    >
      <b-card
        title="Works0"
        img-src="gif/hw0.gif"
        img-top
        style="max-width: 20rem;"
        text-variant="dark"
      >
        <b-card-text>
          私のThree.js初めてのプログラムです、一つモデル動きますのアニメーションです。
        </b-card-text>

        <b-button href="http://bevis00.github.io/ex/hw0.html" variant="primary"
          >Link</b-button
        >
      </b-card>
    </b-jumbotron>
  </div>
</template>

<script></script>

<style lang="scss">
html,
body {
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100%;
  width: 100%;
}

#content1 {
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
}
</style>
