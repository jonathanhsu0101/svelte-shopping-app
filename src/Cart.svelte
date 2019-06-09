<script>
  export let items;
</script>

<style>
  ul {
    list-style: none;
    margin: 1rem;
    padding: 0;
  }

  li {
    margin: 0.5rem 0;
    padding: 0.5rem;
    border: 1px solid #ccc;
  }

  h1 {
    font-size: 1.5rem;
    margin: 1rem;
  }
</style>

<ul>
  {#each items as item}
    <li>{item.title} - {item.price}</li>
  {/each}
</ul>

<h1>TOTAL: $...</h1>
