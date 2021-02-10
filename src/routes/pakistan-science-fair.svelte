<script>
  import Navbar from "../components/Navbar.svelte";
  import Footernav from "../components/FooterNav.svelte";
  import Footer from "../components/Footer.svelte";
</script>

<svelte:head>
  <!-- Required meta tags -->
  <meta charset="utf-8" />
  <meta
    name="viewport"
    content="width=device-width, initial-scale=1, shrink-to-fit=no"
  />

  <!-- Bootstrap CSS -->
  <link
    rel="stylesheet"
    href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.0/css/bootstrap.min.css"
    integrity="sha384-SI27wrMjH3ZZ89r4o+fGIJtnzkAnFs3E4qz9DIYioCQ5l9Rd/7UAa8DHcaL8jkWt"
    crossorigin="anonymous"
  />
  <link
    rel="shortcut icon"
    href="../img/favicon.png"
    type="img/x-icon"
  /><script>
	  src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js">
  </script><script src="./vendor/jquery/jquery-3.2.1.min.js"></script><link
    rel="stylesheet"
    href="https://use.typekit.net/mot4yma.css"
  />
  <link rel="stylesheet" href="https://use.typekit.net/tfs4sks.css" />

  <title>Pakistan Science Fair</title>

  <meta name="description" content="Nathan Redpath, A Creative Designer." />
  <meta
    name="keywords"
    content=" Graphic Design, Interactive, Motion Graphics, Video Production, Web Design, UI, UX"
  />
</svelte:head>

<main>
  <Navbar />
  <div class="animate-in">
    <div class="container-fluid full-width">
      <div class="row row-no-gutter">
        <div class="col-sm-12">
          <div class="work-1">
            <img
              src="img/data-science-fair/1.jpg"
              class="img-full-width"
              alt=""
            />
          </div>
        </div>

        <div class="col-sm-6">
          <div class="left-work">
            <h2 class="work-para">
              <p class="work-head">Pakistan Science Fair</p>
              Print and Digital marketing for the Pakistan Science Fair Award 2020.
              Digital assets produced for print and screens and also an invite for
              the President of Pakistan to attend the event.
            </h2>
          </div>
        </div>
        <div class="col-sm-6">
          <div class="right-work">
            <!-- svelte-ignore a11y-missing-attribute -->
            <img class="work-2" src="../img/data-science-fair/head.jpg" />
          </div>
        </div>

        <div class="col-sm-12">
          <div class="work-1">
            <img
              src="img/data-science-fair/3.jpg"
              class="img-full-width"
              alt=""
            />
          </div>
        </div>

        <div class="col-sm-12">
          <div class="work-1">
            <img
              src="img/data-science-fair/4.jpg"
              class="img-full-width"
              alt=""
            />
          </div>
        </div>

        <div class="col-sm-12">
          <div class="work-1">
            <img
              src="img/data-science-fair/5.jpg"
              class="img-full-width"
              alt=""
            />
          </div>
        </div>

        <div class="col-sm-12">
          <div class="work-1">
            <img
              src="img/data-science-fair/6.jpg"
              class="img-full-width"
              alt=""
            />
          </div>
        </div>

        <div class="col-sm-12">
          <div class="work-1">
            <img
              src="img/data-science-fair/7.jpg"
              class="img-full-width"
              alt=""
            />
          </div>
        </div>

        <div class="col-sm-12">
          <div class="work-1">
            <img
              src="img/data-science-fair/8.jpg"
              class="img-full-width"
              alt=""
            />
          </div>
        </div>
      </div>
      <br />
      <div class="row">
        <div class="col-sm-12">
          <div class="video">
            <div class="spotify-embeds">
              <div class="spotify-embed">
                <!-- svelte-ignore a11y-missing-attribute -->
                <iframe
                  src="https://player.vimeo.com/video/393438633"
                  width="640"
                  height="360"
                  frameborder="0"
                  webkitallowfullscreen
                  mozallowfullscreen
                  allowfullscreen
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <Footernav />
  <Footer />
</main>

<style>
  @font-face {
    font-family: "sofia-pro";
    src: url("/css/fonts/SofiaProBlack.ttf");
  }

  * {
    font-family: sofia-pro, sans-serif;
    font-style: normal;
    font-weight: 300;
  }

  main {
    margin: -10px;
    padding: 0;
    background-color: #fff;
    overflow-x: hidden;
  }

  .animate-in {
    -webkit-animation: fadeIn 1s ease-in;
    animation: fadeIn 1s ease-in;
  }

  @-webkit-keyframes fadeIn {
    from {
      opacity: 0;
    }

    to {
      opacity: 1;
    }
  }

  @keyframes fadeIn {
    from {
      opacity: 0;
    }

    to {
      opacity: 1;
    }
  }

  :global(body) {
    overflow-x: hidden;
  }

  .work-head {
    text-align: center;
    line-height: 1.8em;
    letter-spacing: 0.46em;
    font-weight: 300;
    font-size: 0.5em;
  }

  .work-para {
    padding: 20%;
    text-align: center;
    font-size: 230%;
    line-height: 1.6em;
    font-weight: 400;
    letter-spacing: -0, 1em;
    max-width: 32em;
    font-family: sofia-pro, sans-serif;
    font-style: normal;
    font-weight: 400;
    color: #4b4b4b;
    margin: 0 auto;
  }

  .work-2 {
    padding: 3em;
    width: auto;
    height: auto;
    max-width: 100%;
    max-height: 100%;
  }

  .video {
    text-align: center;
  }

  .container-fluid.full-width {
    padding-left: 0;
    padding-right: 0;
    overflow-x: hidden;
  }

  .row.row-no-gutter {
    margin-left: 0;
    margin-right: 0;
  }

  .row.row-no-gutter [class*="col-"] {
    padding-left: 0;
    padding-right: 0;
  }

  .img-full-width {
    width: 100%;
    height: 100%;
  }

  @import url("//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css");
</style>
