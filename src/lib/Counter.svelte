<script>
  let count = $state(0)
  const increment = () => {
    count += 1
  }

  let counter = $state(0)
  const incrementCounter = () => {
    counter += 2
  }

</script>



<button onclick={incrementCounter}>
  count is {counter}
</button>

<button onclick={increment}>{count}</button>