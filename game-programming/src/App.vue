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
            title="Works 0"
            img-src="gif/hw0.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              Three.jsを使って初めてのプログラムです。モデルが動くアニメーションです。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ex/hw0.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>

          <b-card
            title="Works 1"
            img-src="gif/hw1.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              初めて操作できるThree.jsのプログラムです。操作について、リンク内のページの上部に提示されています。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ex/hw1.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>

          <b-card
            title="Works 2"
            img-src="gif/hw2.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              横スクロールゲームの試作品です。目的はカメラと操作することを組み合わせるに実験します。あとスクロールバックグラウンドや色々なテクスチャを試しました。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ex/hw2.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>

          <b-card
            title="Works 3"
            img-src="gif/hw3.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              このプログラムは前の作品の応用を伸ばします。ゲーム性を増やすために、スプライトのアバターに元のローリングボールを変更して、地形変化を追加し、操作する時のサウンドエフェクトも追加しました。操作について、方向キーがアバターを移動させて、スペースキーがアバターをジャンプさせます。（音量を注意してください）
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ex/hw3.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>

          <b-card
            title="Works 4"
            img-src="gif/hw4.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              マウスを操作して、グリッド内にマウスの左ボタンをクリックして、その時円盤状のモデルはクリックした場所に移動します。すると、円盤状のモデルは小さいアバターたちに追跡られることになります。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ex/hw4.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>

          <b-card
            title="Works 5"
            img-src="gif/hw5.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              これは人体のアニメーションです、動作のインスピレーションの源は<a
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
            title="Works 6"
            img-src="gif/hw6.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              このプログラムは人体のボールピッチングのシミュレーションアニメーションです。ボールが投げられた後、ボールの動きの線に動きの跡が描かれます。
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
