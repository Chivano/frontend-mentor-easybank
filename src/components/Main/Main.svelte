<script>
</script>

<main class="main">
  <div class="background" />
  <div class="picture" />
</main>

<style>
  .main {
    display: grid;
    height: 500px;
  }
  .picture {
    background: url("/image-mockups.png");
    background-repeat: no-repeat;
    background-position: bottom;
    background-size: cover;
    grid-column: 1;
    grid-row: 1;
  }

  .background {
    background: url("/bg-intro-mobile.svg");
    background-repeat: no-repeat;
    grid-column: 1;
    grid-row: 1;
    background-size: cover;
  }
  @media screen and (min-width: 700px) {
    .main {
      display: grid;
      position: relative;
      height: 500px;
    }
    .picture {
      grid-column: 1;
      grid-row: 1;
      background-position-y: -120px;
    }
    .background {
      background: url("/bg-intro-desktop.svg");
      background-repeat: no-repeat;
      grid-column: 1;
      grid-row: 1;
    }
    .mobile-background {
      background-size: cover;
      display: none;
    }
  }
</style>
