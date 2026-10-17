<script>
  let count = 0;

  function increment() {
    count++;
    const counterBtn = document.getElementById("counter");
    if (counterBtn){
      counterBtn.innerHTML = "Counter : " + count + " ";
    }
  }
</script>

<h1 id="counter">Counter : {count}</h1>

<button onclick={increment}>Increment</button>
