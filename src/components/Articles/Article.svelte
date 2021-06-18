<script>
  export let pictureUrl;
  export let title;
  export let author;
  export let text;
</script>

<div class="wrapper">
  <img class="image" src={pictureUrl} alt="" />
  <div class="summary">
    <address class="author">By {author}</address>
    <h3 class="title">{title}</h3>
    <p>{text}</p>
  </div>
</div>

<style>
  .summary {
    padding: 1rem;
  }
  .wrapper {
    padding: 1rem;
    color: hsl(233, 8%, 62%);
  }
  .title {
    color: hsl(233, 26%, 24%);
    font-weight: 300;
  }
  .author {
    font-size: small;
  }
  .image {
    border-radius: 0.5rem 0.5rem 0 0;
    max-width: 100%;
  }
</style>
