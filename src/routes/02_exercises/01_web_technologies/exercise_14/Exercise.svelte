<style>
  .selected {
    background-color:yellow;
  }
</style>

<script>
  let current = "";
</script>

<!-- We will cover buttons later on! -->
<button class="btn btn-secondary" on:click={() => (current = "messi")} class:selected={current === "messi"}>
  Messi
</button>

<button class="btn btn-secondary" on:click={() => (current = "ronaldo")} class:selected={current === "ronaldo"}>
  Ronaldo
</button>

<button class="btn btn-secondary" on:click={() => (current = "neymar")} class:selected={current === "neymar"}>
  Neymar
</button>
