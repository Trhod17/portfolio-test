<script context="module" lang="ts">
  export const prerender = true;
</script>

<script lang="ts">
  import Hero from "../components/hero.svelte";
  import About from "../components/about.svelte";
  import Work from "../components/work.svelte";
  import Projects from "../components/projects.svelte";
  import Tech from "../components/tech.svelte";
  import Navbar from "../components/navbar.svelte";
  import { scrollRef, scrollTo } from "svelte-scrolling";
</script>

<svelte:head>
  <title>Thomas Rhodes</title>
  <meta name="description" content="Svelte demo app" />
</svelte:head>

<Navbar />

<section use:scrollRef={"hero"}>
  <Hero />
</section>
<section use:scrollRef={"aboutme"}>
  <div class="p-16" />
  <About />
  <div class="p-5" />
</section>
<section use:scrollRef={"work"}>
  <div class="p-7" />
  <Work />
</section>
<section use:scrollRef={"projects"}>
  <div class="p-7" />
  <Projects />
</section>
<section use:scrollRef={"tech"}>
  <Tech />
</section>
