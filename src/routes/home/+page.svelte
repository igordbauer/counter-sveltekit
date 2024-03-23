<script>
  let count = 0;
</script>

<h1>Welcome to SvelteKit</h1>

<h1>Counter</h1>

<div>
  <button on:click={() => (count = count + 1)}>Inc</button>
  <p>{count}</p>
  <button on:click={() => (count = count - 1)}>Dec</button>
  <button on:click={() => (count = count * 2)}>2x</button>
</div>

<style>
  div {
    display: flex;
  }
  button {
    margin: 10px;
  }
</style>
