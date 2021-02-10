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
  /><script
    src="https://use.fontawesome.com/10c0d26ba4.js"></script><!-- Bootstrap CSS -->
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

  <title>Contact</title>

  <meta name="description" content="Nathan Redpath, A Creative Designer." />
  <meta
    name="keywords"
    content=" Graphic Design, Interactive, Motion Graphics, Video Production, Web Design, UI, UX"
  />
</svelte:head>

<main>
  <Navbar />
  <div class="animate-in">
    <div class="container">
      <br /><br />

      <div class="row">
        <div class="col-sm-6">
          <br />

          <p class="about-me">
            My name is <span class="highlight">Nate</span>. Currently, I'm an
            <span class="highlight">Interactive Media</span>
            student within my final semester. Previously, I was a creative designer
            for
            <a href="https://www.ulster.ac.uk/"
              ><span class="highlight">Ulster University</span></a
            >
            working on creative outputs & strategy. I am invested in projects initiates
            a <span class="highlight">creative difference</span> in the world. I
            am always freelancing and taking on projects in my spare time.<br
            /><br />Want to work together? Drop me a
            <a href="mailto:nathanredpath10@icloud.com">
              <span class="highlight">line</span></a
            >
          </p>

          <br /><br />

          <div class="mapouter">
            <div class="gmap_canvas">
              <!-- svelte-ignore a11y-missing-attribute -->
              <iframe
                width="500"
                height="300"
                id="gmap_canvas"
                src="https://goo.gl/maps/HomP17NnqQF8H6PC7"
                frameborder="0"
                scrolling="no"
                marginheight="0"
                marginwidth="0"
              />
            </div>
            <br /><br /><style>
              .mapouter {
                position: relative;
                text-align: right;
                height: 300px;
                width: 500px;
              }

              .gmap_canvas {
                overflow: hidden;
                background: none !important;
                height: 300px;
                width: 500px;
              }

              @media screen and (max-width: 1200px) {
                .mapouter {
                  display: none;
                }
              }
            </style>
          </div>
          <br />
        </div>

        <div class="col-sm-3">
          <br />
          <h4>Services</h4>
          <br />Brand identity
          <br />Logo design
          <br />Graphic design
          <br />Illustration
          <br />Art direction
          <br />Website design
          <br />Interaction design
          <br />UI/UX design
          <br />Product packaging
          <br />Signage
          <br />Book and publication design
          <br />Marketing collateral
          <br />Motion graphics
          <br />Animation
          <br />Filmography
          <br />Transmedia narratives
          <br />Photography
        </div>
        <br />
        <br />
        <div class="col-sm-3">
          <br />
          <h4>Clients</h4>
          <br />Ulster University
          <br />Enchanted Touch
          <br />National University of Science and Technology
          <br />National University of Computer and Emerging Sciences (FAST)
          <br />Bahria University
          <br />Air University
          <br />Forum for Adult Learning
        </div>
        <br />
      </div>
    </div>
  </div>
</main>

<style>
  @font-face {
    font-family: "sofia-pro";
    src: url("/img/fonts/Sweety Strawberry.ttf");
  }

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

  .highlight {
    font-family: sweety strawberry;
    opacity: 100%;
    letter-spacing: 1px;
  }

  /* unvisited link */
  a:link {
    color: black;
  }

  /* visited link */
  a:visited {
    color: black;
  }

  /* mouse over link */
  a:hover {
    color: black;
  }

  /* selected link */
  a:active {
    color: black;
  }

  @import url("//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css");
</style>
