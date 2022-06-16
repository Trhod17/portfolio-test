<script lang="ts">
  import { page } from "$app/stores";
  import { scrollTo } from "svelte-scrolling";

  export let path: string;
  export let name: string;
</script>

<li>
  <a
    class:btn-active={$page.url.pathname === path}
    class:bg-neutral-focus={$page.url.pathname === path}
    class:text-neutral-content={$page.url.pathname === path}
    href="/"
    sveltekit:noscroll
    use:scrollTo={path}
    class="bg-secondary text-secondary-content mr-3 px-3 hover:bg-secondary-focus">{name}</a
  >
</li>
