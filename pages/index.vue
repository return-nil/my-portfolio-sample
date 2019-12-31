<template>
 <div id="wrapper">
    <header id="header">
      <h1 class="logo">
        <span class="logo-title">Taro's portfolio</span>
        <span class="logo-desc">Web Engineer</span>
      </h1>
    </header>
    <nav id="gnav">
      <ul>
        <li><i class="fas fa-user fa-lg"><a href="#Profile">PROFILE</a></i></li>
        <li><i class="fas fa-lightbulb fa-lg"><a href="#skill">SKILL</a></i></li>
        <li><i class="fas fa-envelope fa-lg"><a href="#contact">CONTACT</a></i></li>
      </ul>
    </nav>
    <main id="contents">

      <section class="section" id="Profile">
        <div class="inner">
          <div class="section-title-block">
            <h2 class="section-title"><i class="fas fa-user"><span class="section-title-css">PROFILE</span></i></h2>
          </div>
          <div class="two-column-wrapper">
            <div class="two-column-image profile">
              <img src="~/assets/images/40705236.jpeg" alt="">
            </div>
            <div class="two-column-desc">
              <p class="text">
              　はじめまして。たろうと申します。<br>
              　ここ５年ほどRuby on Railsで主にバックエンドの開発をしてきました。<br>
                　今はフロントもやりたいと思い絶賛勉強中です。<br>
                　好きな言語はRubyであまり好きでない言語はPHPです。<br>
                　golangもこれから勉強しようと思っております。
              </p>
            </div>
          </div>
        </div>
      </section>
      
      <section class="section" id="skill">
        <div class="inner">
          <div class="section-title-block">
            <h2 class="section-title"><i class="fas fa-lightbulb fa-lg"><span class="section-title-css">SKILL</span></i></h2>
            <p class="section-desc"></p>
          </div>
          <div class="card-wrapper">
            <div class="card">
              <div class="skill-desc">
                <h3 class="skill-desc-title"><i class="fas fa-desktop"></i>バックエンド</h3>
                <p>ここ５年Ruby on Railsで開発しています。</p>
                <table class="table table-borderless">
                  <thead>
                    <tr>
                      <th scope="col">技術</th>
                      <th scope="col">経験年数</th>
                      <th scope="col">スキル</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <th scope="row">Ruby on Rails</th>
                      <td>5年</td>
                      <td><span class="rating"><p class="rate rate5"></p></span></td>
                    </tr>
                    <tr>
                      <th scope="row">PHP</th>
                      <td>1年</td>
                      <td><span class="rating"><p class="rate rate2"></p></span></td>
                    </tr>
                    <tr>
                      <th scope="row">golang</th>
                      <td>勉強中</td>
                      <td><span class="rating"><p class="rate rate1"></p></span></td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>

            <div class="card">
              <div class="skill-desc">
                <h3 class="skill-desc-title"><i class="fas fa-desktop"></i>フロントエンド</h3>
                <p>サブとしてフロントも少し触っております。</p>
                <table class="table table-borderless">
                  <thead>
                    <tr>
                      <th scope="col">技術</th>
                      <th scope="col">経験年数</th>
                      <th scope="col">スキル</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <th scope="row">JavaScript </th>
                      <td>3年</td>
                      <td><span class="rating"><p class="rate rate3"></p></span></td>
                    </tr>
                    <tr>
                      <th scope="row">jQuery</th>
                      <td>2年</td>
                      <td><span class="rating"><p class="rate rate3"></p></span></td>
                    </tr>
                    <tr>
                      <th scope="row">Vue.js</th>
                      <td >半年</th>
                      <td><span class="rating"><p class="rate rate1"></p></span></td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>

            <div class="card">
              <div class="skill-desc">
                <h3 class="skill-desc-title"><i class="fas fa-database"></i>DB</h3>
                <p>MySQLを使用することが多いです。</p>
                <table class="table table-borderless">
                  <thead>
                    <tr>
                      <th scope="col">技術</th>
                      <th scope="col">経験年数</th>
                      <th scope="col">スキル</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <th scope="row">MySQL</th>
                      <td>4年</td>
                      <td><span class="rating"><p class="rate rate4"></p></span></td>
                    </tr>
                    <tr>
                      <th scope="row">PostgreSQL</th>
                      <td>1年</td>
                      <td><span class="rating"><p class="rate rate3"></p></span></td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>

            <div class="card">
              <div class="skill-desc">
                <h3 class="skill-desc-title"><i class="fas fa-server"></i>インフラ・サーバー</h3>
                <p>AWSではEC2、RDS、Athena等を触っています。</p>
                <table class="table table-borderless">
                  <thead>
                    <tr>
                      <th scope="col">技術</th>
                      <th scope="col">経験年数</th>
                      <th scope="col">スキル</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <th scope="row">AWS(EC2、RDS等)</th>
                      <td>1年</td>
                      <td><span class="rating"><p class="rate rate3"></p></span></td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>

            <div class="card">
              <div class="skill-desc">
                <h3 class="skill-desc-title"><i class="fas fa-toolbox"></i>その他</h3>
                <p>開発等で使用したツールやFWです。</p>
                <table class="table table-borderless">
                  <thead>
                    <tr>
                      <th scope="col">技術</th>
                      <th scope="col">経験年数</th>
                      <th scope="col">スキル</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <th scope="row">Docker</th>
                      <td>2年</td>
                      <td><span class="rating"><p class="rate rate3"></p></span></td>
                    </tr>
                    <tr>
                      <th scope="row">git</th>
                      <td>4年</td>
                      <td><span class="rating"><p class="rate rate4"></p></span></td>
                    </tr>
                    <tr>
                      <th scope="row">CircleCI</th>
                      <td>2年</td>
                      <td><span class="rating"><p class="rate rate2"></p></span></td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="section" id="contact">
        <div class="inner">
          <div class="section-title-block">
            <h2 class="section-title"><i class="fas fa-envelope fa-lg"><span class="section-title-css">CONTACT</span></i></h2>
            <p class="section-desc">
              何かありましたらtwitterのDMからご連絡をください。
            </p>
          </div>
          <div class="contact-wrapper">
            <div class="contact-list" style="text-align: center;">
                <a href="https://twitter.com/return_nil_" target="_blank"><img src="~/assets/images/40705236.jpeg" alt="" class="contact-img"  style="margin: 0 auto;"><span class="contact-list-desc">Twitter</span></a>
            </div>
          </div>
        </div>
      </section>
      
    </main>
    <footer id="footer">
      <div class="inner">
        <nav class="footer-link">
          <ul>
            <li><a href="#Profile">Profile</a></li>
            <li><a href="#skill">SKILL</a></li>
            <li><a href="#contact">CONTACT</a></li>
          </ul>
        </nav>
        <p class="copyright">Copyright&copy;Taro. All Rights Reserved.</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: 'Taro\'s portfolio',
      meta: [
        // `hid` は一意の識別子として使用されます。 `vmid` は動作しないので使わないでください。
        { name: 'viewport', content: 'width=device-width,initial-scale=1.0,user-scalable=no' },
        { property: 'og:type', content: 'website' },
        { property: 'og:title', content: 'たろう ポートフォリオ' },
        { property: 'og:url', content: 'URL入る' },
        { property: 'og:description', content: 'たろうのポートフォリオです。' },
        { property: "og:image", content: "img/ogp.png" },
        { name: "description", content: "たろうのポートフォリオです。" },
        { href: "https://fonts.googleapis.com/css?family=Yesteryear", rel: "stylesheet" },
        { href: "https://fonts.googleapis.com/css?family=Oswald:700", rel: "stylesheet" },
        { href: "https://fonts.googleapis.com/css?family=Open+Sans:700", rel:"stylesheet" },
        { href: "css/reset.css", media: "all", rel: "stylesheet", type: "text/css" },
        { href: "css/photoswipe/photoswipe.css", media: "all", rel: "stylesheet", type: "text/css" },
        { href: "css/photoswipe/default-skin/default-skin.css", media: "all", rel: "stylesheet", type: "text/css" },
        { href: "css/style.css", media: "all", rel: "stylesheet", type: "text/css" },
        { rel: "stylesheet",  href: "https://use.fontawesome.com/releases/v5.2.0/css/all.css", integrity: "sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ", crossorigin: "anonymous" },
        { rel: "shortcut icon", href: "img/favicon2.ico" },
        { rel: "stylesheet", href: "https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css", integrity: "sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO", crossorigin: "anonymous" }
      ]
    }
  }
}
</script>
