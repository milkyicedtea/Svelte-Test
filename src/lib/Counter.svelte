<script lang="ts">
  let count: number = 0
  function increment() {
    count += 1
  }
</script>

<button on:click={increment}>
  count is {count}
</button>
