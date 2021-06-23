<script>
</script>

<main class="main">
  <img class="mobile-background" src="./bg-intro-mobile.svg" />
  <img class="picture" src="./image-mockups.png" />
</main>

<style>
  .main {
    height: 100%;
    position: relative;
  }
  .picture {
    clip-path: inset(140px 0px 0px 0px);
    transform: translateY(-140px);
    width: 100%;
    top: 0;
    bottom: 0;
    position: absolute;
  }
  .desktop-background {
    display: none;
  }
  .mobile-background {
    position: absolute;
    width: 100%;

    left: 0;
    right: 0;
    transform: scaleY(0.8);
    transform-origin: top;
  }
  @media screen and (min-width: 700px) {
    .main {
      height: 100%;
      position: relative;
    }
    .picture {
      clip-path: inset(80px 0px 0px 0px);
      transform: translateY(-80px);
      width: 80%;
    }
    .desktop-background {
      position: absolute;
      display: block;
      width: 100%;
      transform: translateY(-250px);
      transform-origin: top;
    }
    .mobile-background {
      display: none;
    }
  }
</style>
