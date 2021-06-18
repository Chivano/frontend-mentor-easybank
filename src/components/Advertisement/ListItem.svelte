<script>
  export let imageSrc;
  export let title;
  export let text;
</script>

<div class="wrapper">
  <li class="listItem">
    <img src={imageSrc} alt="" />
    <h2 class="header">{title}</h2>
    <p class="text">{text}</p>
  </li>
</div>

<style>
  .header {
    text-align: center;
    font-weight: 400;
    color: hsl(233, 26%, 24%);
  }
  .wrapper {
    display: flex;
    justify-content: center;
    padding: 2rem;
  }
  .listItem {
    display: flex;
    flex-direction: column;
    align-items: center;
    list-style: none;
  }
  .text {
    color: hsl(233, 8%, 62%);
    text-align: center;
  }
</style>
