<script>
  import Navbar from "../components/Navbar.svelte";
  import Footernav from "../components/FooterNav.svelte";
  import Footer from "../components/Footer.svelte";
</script>

<svelte:head>
  <title>Lockdown</title>
</svelte:head>

<main>
  <Navbar />
  <div class="animate-in">
    <div class="container-fluid full-width">
      <div class="row row-no-gutter">
        <div class="col-sm-12">
          <div class="work-1">
            <img src="/img/lockdown/1.png" class="img-full-width" alt="" />
          </div>
        </div>

        <div class="col-sm-6">
          <div class="left-work">
            <h2 class="work-para">
              <p class="work-head">Lockdown</p>
              The major project was to provide an understanding of media Literacy,
              news media literacy and transliteracy for research as practice production.
              Utilisiing conspiracy, fake news and audience tracking to provide and
              intervention on how audiences consume the news.
            </h2>
          </div>
        </div>
        <div class="col-sm-6">
          <div class="right-work">
            <!-- svelte-ignore a11y-missing-attribute -->
            <img class="work-2" src="/img/lockdown/head.png" />
          </div>
        </div>

        <div class="col-sm-12" />

        <div class="col-sm-12">
          <div class="work-1">
            <img src="img/lockdown/2.png" class="img-full-width" alt="" />
          </div>
        </div>

        <br />
        <div class="col-sm-12">
          <div align="center" class="socialbtns">
            <ul>
              <li>
                <a href="/img/lockdown/productionlog.pdf">
                  <div id="contact-icon">
                    <p class="pcontact">Production Log</p>
                  </div>
                </a>
              </li>

              <li>
                <a href="https://lockdown.digital/">
                  <div id="contact-icon">
                    <p class="pcontact">Website</p>
                  </div>
                </a>
              </li>

              <li>
                <a href="/img/lockdown/exegisis.pdf">
                  <div id="contact-icon">
                    <p class="pcontact">Exegisis</p>
                  </div>
                </a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <Footernav />
    <Footer />
  </div>
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

  :global(body) {
    overflow-x: hidden;
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

  *.socialbtns {
    margin-left: 2%;
  }

  .socialbtns,
  .socialbtns ul,
  .socialbtns li {
    float: left;
  }

  .socialbtns ul,
  .socialbtns li {
    margin-left: 32px;
  }

  .socialbtns li {
    list-style: none outside none;
    display: inline-block;
    text-decoration: none;
    padding-top: 22px;
    position: relative;
    cursor: pointer;
  }

  #contact-icon {
    width: 120%;
    height: 40px;
    color: #000;
    background-color: #fff;
    border: 1px solid #000;
    border-radius: 22px;
    -moz-border-radius: 22px;
    -webkit-border-radius: 22px;
    -o-border-radius: 22px;
    cursor: pointer;
  }

  #contact-icon:hover {
    color: #fff;
    background-color: #000;
    border: 1px solid #000;
    transition-duration: 0.5s;
    cursor: pointer;
    text-decoration: none;
  }

  .pcontact {
    text-align: center;
    vertical-align: middle;
    padding: 5%;
    text-decoration: none;
  }

  .pcontact:hover {
    color: #fff;
    text-decoration: none;
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
