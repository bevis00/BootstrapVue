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
            title="Works 1"
            img-src="gif/hw1.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              これは操作できるストップウォッチのモデルです。このプログラムの作り方はカメラの画角を固定して、2Dモデルの前にセットします。カメラが固定されているから、この画面は固定するウェブページのようにプレゼンテーションされます。モデルの作り方はPNG画像のバックグラウンドを消して、そしてフラットモデルに貼り付けます。次はフラットモデルの透明度の値がtrueに設定します。三つボタンとポインタの回転機能を作って、さらに組み合わせたあとこのプログラムが完成です。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ComputerGraphics/hw1.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>

          <b-card
            title="Works 2"
            img-src="gif/hw3.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              小さな戦車ゲームです。一人称視点と三人称視点その二つ視点があります。Switch Cameraボタンをクリックして、視点が切り替えさせられます。戦車を移動して、ターゲットを砲撃することができます。ターゲットが砲撃られた後、ターゲットが新しい位置にリセットします。操作について、リンク内のページの上部に提示されています。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ComputerGraphics/hw3.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>

          <b-card
            title="Works 3"
            img-src="gif/hw4.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              今回は自分のモデルを使いません。ネットで無料のモデルをダウンロードして、そして、ダウンロードしたモデルでロードを試します。車のモデルを探した後、シーン内にロードします。次は初めて分割画面を使用します。先ずは、二つのカメラを作って、一つはグリッドの真上にセットして、もう一つはシーン内の車のモデルの後ろにセットします。最後はシーン内の車を操作して、二つの画角でプレゼンテーションを観察します。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/ComputerGraphics/hw4.html"
              variant="primary"
              >Link</b-button
            >
          </b-card>

          <b-card
            title="Works 4"
            img-src="gif/hw5.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              Three.jsを使って、部屋の机のシーンをシミュレーションします。机や椅子や電気スタンドなど色々なモデルをロードします。電灯コントロールのリモコンを作って、机の上にセットします。ボタンをクリックして、リモコンのボタンや電灯のプレゼンテーションを観察します。
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
