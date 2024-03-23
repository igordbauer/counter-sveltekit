<script>
  let count = 0;
</script>

<h1>Welcome to SvelteKit</h1>
<p>
  Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
</p>

<h1>Counter</h1>

<div>
  <button on:click={() => (count = count + 1)}>Inc</button>
  <p>{count}</p>
  <button on:click={() => (count = count - 1)}>Dec</button>
</div>
<div>
  <button on:click={() => (count = count + 1)}>Inc</button>
  <p>{count}</p>
  <button on:click={() => (count = count - 1)}>Dec</button>
</div>

<style>
  div {
    display: flex;
  }
  button {
    margin: 10px;
  }
</style>
