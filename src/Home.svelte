<script>
  let seconds = 0;
  const interval = setInterval(_ => { seconds = seconds + 1 }, 1000);
  onDestroy(_ => clearInterval(interval));
</script>

<main>
  <p>Has been running for { seconds } seconds!</p>
</main>

<style>

</style>
