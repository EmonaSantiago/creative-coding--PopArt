<script>
  import "../routes/+page.svelte";
  import "./../styles/global.css";
</script>

<slot />
<footer />

<style>
  @font-face {
    font-family: "BADABB";
    src: url("/assets/Fonts/BADABB__.TTF");
  }

  body {
    font-family: "BADABB";
  }
</style>
