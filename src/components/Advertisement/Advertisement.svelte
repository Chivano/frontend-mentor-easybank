<script>
  import ListItem from "./ListItem.svelte";
</script>

<div class="articles">
  <ListItem
    text=" Our modern web and mobile applications allow you to keep track of your
finances wherever you are in the world."
    title="Online Banking"
    imageSrc="./icon-online.svg"
  />
  <ListItem
    text="See exactly where your money goes each month. Receive notifications when you're close to ypur hitting limits"
    title="Simple Budgeting"
    imageSrc="./icon-budgeting.svg"
  />
  <ListItem
    text="We don't do branches. Open your account in minutes online and start taking control of your finances right away."
    title="Fast Onboarding"
    imageSrc="./icon-onboarding.svg"
  />
  <ListItem
    text="Manage your savings, investments, pension, and much more from one account. Tracking your money has never been easier."
    title="Open API"
    imageSrc="./icon-api.svg"
  />
</div>

<style>
  .articles {
    background-color: hsl(0, 0%, 98%);
  }
</style>
