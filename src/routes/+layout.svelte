<script>
  import "../app.css";
</script>

<slot />

<style>

:global(body) {
    background-color: var(--bg);
    font-family: "Fira Code", monospace;
    letter-spacing: 0.1em; /* Adjust as needed */
    color: var(--white);
  }

</style>