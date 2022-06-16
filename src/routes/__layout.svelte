<script lang="ts">
  import "../app.css";
</script>

<svelte:head />

<main>
  <slot />
</main>

<footer class="max-w-screem w-full p-4 text-base-content footer footer-center mt-20 border-t-2">
  <div>
    <p>
      CopyLeft <span class="copy-left">&copy;</span> 2022 - Thomas Rhodes - The source code is
      <a class="link-primary" href="https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html">GPL2</a>
    </p>
  </div>
</footer>

<style>
  .copy-left {
    display: inline-block;
    transform: rotate(180deg);
  }
</style>
