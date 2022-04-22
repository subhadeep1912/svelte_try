<script>
 import Counter from "./lib/Counter.svelte";
 import LeftCard from "./lib/LeftCard.svelte"
 import RightCard from "./lib/RightCard.svelte"
</script>

<main>
  <div class="left">
<LeftCard />
</div>
<div class="right">
<RightCard />
</div>
</main>

<style>
  main {
    display: flex;
    flex-direction: row;
  }
  .left {
    flex-grow: 1;
  }
  .right {
    flex-grow: 1;
  }
</style>
