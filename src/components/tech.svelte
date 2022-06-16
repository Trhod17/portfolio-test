<script lang="ts">
  import Techwidget from "./techwidget.svelte";
</script>

<a id="tech" class="w-100 text-center">
  <span class="divider" />
  <h1 class="mb-5 text-5xl font-bold underline">Technologies I Use</h1>
  <div class="grid grid-cols-5 auto-cols-max w-8/12 mx-auto gap-3 justify-center">
    <Techwidget tech="svelte" />
    <Techwidget tech="sveltekit" />
    <Techwidget tech="python" />
    <Techwidget tech="daisyui" />
    <Techwidget tech="tailwind" />
    <Techwidget tech="latex" />
    <Techwidget tech="typescript" />
  </div>
</a>
