<template>
  <div id="app">
    <b-jumbotron
      id="content1"
      bg-variant="secondary"
      text-variant="light"
      header-level="4"
    >
      <h1 align="center">
        <font face="Bookman Old Style">Game Programming </font>
      </h1>
      <h1 align="center" id="title2">
        <font face="Bookman Old Style">Works List</font>
      </h1>

      <div align="center">
        <b-card-group id="cardGroup" columns>
          <b-card
            title="Works0"
            img-src="gif/hw0.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              私のThree.js初めてのプログラムです、一つモデル動きますのアニメーションです。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ex/hw0.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>

          <b-card
            title="Works1"
            img-src="gif/hw1.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              初めて操作できますのThree.jsプログラムです、操作について、中のページの上があります。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ex/hw1.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>

          <b-card
            title="Works2"
            img-src="gif/hw2.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              平らな試作品です、カメラのコントロールの練習です。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ex/hw2.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>

          <b-card
            title="Works3"
            img-src="gif/hw3.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              前の作品の応用を伸ばす、操作に音を追加、操作について、方向キーはアバターの移動です、スペースキーはアバターのジャンプです。（音量を注意してください）
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ex/hw3.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>

          <b-card
            title="Works4"
            img-src="gif/hw4.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              マウスを操作します、グリッド内を左クリック、この時、ディスクはクリックした場所に移動します、いろいろな小さいアバターはディスクに追跡します。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ex/hw4.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>

          <b-card
            title="Works5"
            img-src="gif/hw5.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              これは、人体のアニメーションです、動作のインスピレーションの源は<a
                href="https://www.youtube.com/watch?v=_mkiGMtbrPM"
                >World Order</a
              >のダンスです。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ex/hw5.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>

          <b-card
            title="Works6"
            img-src="gif/hw6.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              人体のボールピッチングアニメーションのシミュレーションです。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ex/hw6.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>
        </b-card-group>
      </div>

      <div align="center">
        <b-button
          pill
          size="lg"
          variant="light"
          href="https://bevis00.github.io/Resume/index.html"
          id="returnBtn"
          >my-web</b-button
        >
      </div>
    </b-jumbotron>
  </div>
</template>

<script></script>

<style lang="scss">
html,
body {
  margin: 0;
  padding: 0;
  max-height: 100%;
  max-width: 100%;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#content1 {
  margin: 0;
  padding-top: 10vh;
  padding-bottom: 10vh;
  padding-left: 10vw;
  padding-right: 10vw;
  max-height: 100%;
  max-width: 100%;
}

#cardGroup {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}

#title2 {
  margin-bottom: 3rem;
}

#returnBtn {
  margin-top: 5rem;
}
</style>
