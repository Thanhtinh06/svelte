<script>
  let count = 0;
  const increment = () => {
    count += 1;
  };
</script>

<button on:click={increment}
  >Click {count} {count === 1 ? "time" : "times"}</button
>

{#if count > 10}
  <p>{count} is getter than 10</p>
{:else if count < 10}
  <p>{count} is lesser than 10</p>
{:else}
  <p>{count} = 10</p>
{/if}
