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
            title="Works1"
            img-src="gif/hw1.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              この作品は初めのjQueryの応用、jQuery通してHTMLを操作する、簡単なタンデム操作です。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/w3d/hw1.html"
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
              初めてThree.jsとjQuery組み合わせる、観る可能なホームモデルを作成する、そして、画面にいくつかの固定画角を提供する、視野角の文字をクリックして、視野角を切り替えます。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/w3d/hw2.html"
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
              会場モデルを作成する、光源の影響を受けるの3Dモデルを使用する、2つの異なる光源を作成する、異なる光源を切り替えることにより、光源通して3Dモデルのプレゼンテーションを観察できます。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/w3d/hw3.html"
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
              これもThree.jsとjQuery組み合わせの応用、右側画面のメニューから選択して、選択した結果は、左側画面をクリックして表示できます。
            </b-card-text>

            <b-button
              href="http://bevis00.github.io/w3d/hw4.html"
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
              ログインシステムのログテスト、実際のアプリケーションは次の作品で組み合わせる、事前作業の記録です。
            </b-card-text>
          </b-card>

          <b-card
            title="Works6"
            img-src="gif/hw6.gif"
            img-top
            style="max-width: 25rem; margin-bottom:2rem;"
            text-variant="dark"
          >
            <b-card-text>
              ウェブページを使用したユーザーの自宅操作のシミュレーション、リンク内は操作の画面記録と操作の説明がある、基本的な原理は、C言語を使用してユーザーデータを記録する、バックエンドでログを生成する、ユーザーはフロントページのログデータを選択して、以前のレコードステータスを復元できます。
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
