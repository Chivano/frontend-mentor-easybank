<script>
  import Button from "../RequestButton/Button.svelte";
</script>

<div class="infowrapper">
  <h1>Next generation digital banking</h1>
  <p>
    Take your financial life online. Your Easybank account will be a
    one-shop-stop for spending, saving, budgeting, investing and much more
  </p>
  <Button />
</div>

<style>
  .infowrapper {
    padding: 2rem;
    text-align: center;
  }

  .infowrapper > H1 {
    font-weight: 100;
  }
  .infowrapper > p {
    color: hsl(233, 8%, 62%);
  }
</style>
