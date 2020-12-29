<template>
  <div id="app">
    <b-jumbotron
      id="content1"
      bg-variant="secondary"
      text-variant="light"
      header-level="4"
    >
      <h1 align="center">
        <font face="Bookman Old Style">Web 3D </font>
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
              このプログラムは初めてのjQueryを応用することです。jQueryを通じてHTMLを操作することに練習します。画面中真ん中のボタンをクリックして、クリスマスツリーのイルミネーションのように、光が輝いている効果があります。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/w3d/hw1.html"
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
              初めてのThree.jsとjQueryを組み合わせるプログラムです。参観できるハウスのモデルを作ります。そして、画面にいくつかの固定画角をセットする。黄色の文字をクリックして、視野角を切り替えます。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/w3d/hw2.html"
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
              絵画展のモデルをシミュレーションするプログラムです。光源の影響を受けられる3Dモデルを使います。そして、二つ異なる光源を作って、異なる光源を切り替えることによって、光源の変化することを通じて3Dモデルのプレゼンテーションを観察できます。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/w3d/hw3.html"
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
              このプログラムはWorks2と同じもThree.jsとjQueryを組み合わせる応用します。右側画面のメニューから選択して、選択した結果は左側画面をクリックして表示できます。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/w3d/hw4.html"
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
              ログインシステムのログテストです。実際の応用することは次の作品で組み合わせます。これは事前作業の記録です。
            </b-card-text>
          </b-card>

          <b-card
            title="Works 6"
            img-src="gif/hw6.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              これはユーザーがウェブサイトで自宅操作することのシミュレーションです。リンク内は操作の画面記録と操作することの説明があります。基本的な原理はC言語を使って、ユーザーデータを記録します。そして、バックエンドにログを生成します。ユーザーはフロントエンドページのログデータを選択して、以前のレコードステータスを復元することができます。
            </b-card-text>

            <b-button
              href="https://docs.google.com/presentation/d/19vJbtNGzy4XiMPIEq2KtMObyE7eocctKPsJrWoHh0Ck/edit#slide=id.p"
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
