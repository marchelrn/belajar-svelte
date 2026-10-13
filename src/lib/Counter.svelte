<script>
  let count = 0;

  function increment() {
    count++;
    document.getElementById("counter").innerHTML = "Counter : " + count + " ";
  }
</script>

<h1 id="counter">Counter : 0</h1>

<button onclick={increment}>Increment</button>
