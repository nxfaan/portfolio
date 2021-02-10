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

  <title>Go Boston</title>

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
            <img src="img/Go-Boston/1.jpg" class="img-full-width" alt="" />
          </div>
        </div>

        <div class="col-sm-6">
          <div class="left-work">
            <h2 class="work-para">
              <p class="work-head">Go Boston</p>
              An Instagram campaign conducted in collaboration with Ulster University
              to promote the international event Go Boston.
            </h2>
          </div>
        </div>
        <div class="col-sm-6">
          <div class="right-work">
            <!-- svelte-ignore a11y-missing-attribute -->
            <img class="work-2" src="/img/Go-Boston/head.jpg" />
          </div>
        </div>

        <div class="col-sm-12">
          <div class="work-1">
            <img src="img/Go-Boston/3.jpg" class="img-full-width" alt="" />
          </div>
        </div>

        <div class="col-sm-12">
          <div class="work-1">
            <img src="img/Go-Boston/2.jpg" class="img-full-width" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
  <Footernav />
  <Footer />

  <!-- Optional JavaScript -->
  <!-- jQuery first, then Popper.js, then Bootstrap JS --><script
    src="https://code.jquery.com/jquery-3.4.1.slim.min.js"
    integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n"
    crossorigin="anonymous">
  </script><script
    src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
    integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo"
    crossorigin="anonymous">
  </script><script
    src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.0/js/bootstrap.min.js"
    integrity="sha384-3qaqj0lc6sV/qpzrc1N5DC6i1VRn/HyX4qdPaiEFbn54VjQBEU341pvjz7Dv3n6P"
    crossorigin="anonymous">
  </script>
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

  .work-head {
    text-align: center;
    line-height: 1.8em;
    letter-spacing: 0.46em;
    font-weight: 300;
    font-size: 0.5em;
  }

  :global(body) {
    overflow-x: hidden;
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
