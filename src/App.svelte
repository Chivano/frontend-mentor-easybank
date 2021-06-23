<script>
  import Navbar from "./components/Navbar/Navbar.svelte";
  import Main from "./components/Main/Main.svelte";
  import Info from "./components/Info/Info.svelte";
  import Advertisement from "./components/Advertisement/Advertisement.svelte";
  import Articles from "./components/Articles/Articles.svelte";
  import Footer from "./components/Footer/Footer.svelte";
  import "@fortawesome/fontawesome-free/js/all.js";
</script>

<Navbar />
<div class="grid">
  <div class="main"><Main /></div>
  <div class="info"><Info /></div>
  <div class="advertisment"><Advertisement /></div>
  <div class="articles"><Articles /></div>
  <div class="footer"><Footer /></div>
</div>

<style>
  @media screen and (min-width: 700px) {
    .grid {
      display: grid;
      height: 100%;
      grid-template-rows: 1fr;
      grid-template-columns: 1fr 1fr;
      grid-template-areas: "info main";
    }
    .info {
      grid-area: info;
    }
  }

  /* latin-ext */
  @font-face {
    font-family: "Public Sans";
    font-style: normal;
    font-weight: 300;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/publicsans/v5/ijwRs572Xtc6ZYQws9YVwnNIfJ7Cww.woff2)
      format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB,
      U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
  }
  /* latin */
  @font-face {
    font-family: "Public Sans";
    font-style: normal;
    font-weight: 300;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/publicsans/v5/ijwRs572Xtc6ZYQws9YVwnNGfJ4.woff2)
      format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA,
      U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212,
      U+2215, U+FEFF, U+FFFD;
  }
  /* latin-ext */
  @font-face {
    font-family: "Public Sans";
    font-style: normal;
    font-weight: 400;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/publicsans/v5/ijwRs572Xtc6ZYQws9YVwnNIfJ7Cww.woff2)
      format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB,
      U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
  }
  /* latin */
  @font-face {
    font-family: "Public Sans";
    font-style: normal;
    font-weight: 400;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/publicsans/v5/ijwRs572Xtc6ZYQws9YVwnNGfJ4.woff2)
      format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA,
      U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212,
      U+2215, U+FEFF, U+FFFD;
  }
  /* latin-ext */
  @font-face {
    font-family: "Public Sans";
    font-style: normal;
    font-weight: 700;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/publicsans/v5/ijwRs572Xtc6ZYQws9YVwnNIfJ7Cww.woff2)
      format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB,
      U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
  }
  /* latin */
  @font-face {
    font-family: "Public Sans";
    font-style: normal;
    font-weight: 700;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/publicsans/v5/ijwRs572Xtc6ZYQws9YVwnNGfJ4.woff2)
      format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA,
      U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212,
      U+2215, U+FEFF, U+FFFD;
  }
</style>
