<script>
  let count = 0
</script>

<main style="font-family: sans-serif; text-align: center; margin-top: 4rem">
  <h1>Svelte + Vite Starter</h1>
  <p>Deployed with <a href="https://pandastack.io">PandaStack</a> ⚡</p>
  <button on:click={() => count++} style="padding: 0.5rem 1.5rem; font-size: 1rem">
    Count: {count}
  </button>
</main>
