<script>
    export let data;
  </script>
  
  <h1>Welcome to SvelteKit</h1>
  {#if data.word}
    <p>the word from the server is: {data.word}</p>
  {:else}
    <p>no word from the server :(</p>
  {/if}
  