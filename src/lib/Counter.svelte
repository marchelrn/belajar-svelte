<script>
  let count = $state(0); // menggunakan reactive state

  function increment() {
    count++;
  }
</script>

<h1>Counter : {count}</h1>

<button onclick={increment}>Increment</button>
