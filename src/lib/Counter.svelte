<script>
  let count = $state([]); // derrived
  let total = $derived(count.reduce((a, b) => a + b, 0));

  function increment() {
    count.push(1);
  }
</script>

<h1>{count.join(" + ")} = {total}</h1>

<button onclick={increment}>Increment</button>
