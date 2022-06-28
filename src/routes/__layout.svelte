<script>
  import "../app.css";
  import Navbar from "./_components/navbar.svelte";
</script>

<div class="h-full">
  <Navbar />
  <div class="h-full">
    <slot />
  </div>
</div>

<style>
  div {
    height: 100%;
  }
</style>
