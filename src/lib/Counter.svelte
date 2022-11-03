<script>
  let count = 0
  const increment = () => {
    count += 1
  }
  const log = (node, opt, etc) => {
    console.log({opt, etc})
    console.log(node)
  }
</script>

<button on:click={increment} use:log>
  count is {count}
</button>
