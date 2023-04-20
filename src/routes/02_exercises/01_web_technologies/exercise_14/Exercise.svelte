<script>
  let current = "";
</script>

<style>
  button.chosen{
    background-color: red;
  }
</style>

<!-- We will cover buttons later on! -->
<button class:chosen={current==="messi"} on:click={() => (current = "messi")}>
  Messi
</button>

<button class:chosen={current==="ronaldo"} on:click={() => (current = "ronaldo")}>
  Ronaldo
</button>

<button class:chosen={current==="neymar"} on:click={() => (current = "neymar")}>
  Neymar
</button>
