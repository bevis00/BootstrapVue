<template>
  <div id="app">
    <b-jumbotron
      id="content1"
      bg-variant="secondary"
      text-variant="light"
      header-level="4"
    >
      <h1 align="center">
        <font face="Bookman Old Style">Computer Graphics </font>
      </h1>
      <h1 align="center" id="title2">
        <font face="Bookman Old Style">Works List</font>
      </h1>

      <div align="center">
        <b-card-group id="cardGroup" columns>
          <b-card
            title="Works1"
            img-src="gif/hw1.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              カメラを使用して2D平面モデルを観る、これはストップウォッチのモデル、作る原理は、フラットモデルにPNG画像つや消しを貼り付ける、そして、フラットモデル透明度の値がtrueに設定されている、完全なストップウォッチを表示できる、ウォッチングを切り替える3つのポインターモードです。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ComputerGraphics/hw1.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>

          <b-card
            title="Works2"
            img-src="gif/hw3.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text
              >小さな戦車ゲーム、一人称視点と三人称視点の切り替えを提供する、戦車を操作してターゲットを撃ちます。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ComputerGraphics/hw3.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>

          <b-card
            title="Works3"
            img-src="gif/hw4.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              車のモデルをシーンにインポートする、分割画面を使用して、さまざまな表示モードで車の操作を見ることができます。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ComputerGraphics/hw4.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>

          <b-card
            title="Works4"
            img-src="gif/hw5.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              Three.jsを使用してシーンでランプ操作のスイッチモデルを作成する、HTMLによって提供されるマウスクリックイベントをスイッチと組み合わせる、異なる光源を切り替えるときに、シーン内モデルの光と影の変化を観察します。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ComputerGraphics/hw5.html"
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
