<script>
  function handleClick() {
    console.log("Request invite");
  }
</script>

<button class="button" on:click={handleClick}>Request invite</button>

<style>
  .button {
    color: white;
    font-family: Public Sans;
    font-weight: 400;
    font-size: 18px;
    border-radius: 2rem;
    padding: 0.5rem 1.5rem 0.5rem 1.5rem;
    background: linear-gradient(
      90deg,
      rgba(49, 211, 92, 1) 0%,
      rgba(43, 183, 218, 1) 89%
    );
  }
</style>
