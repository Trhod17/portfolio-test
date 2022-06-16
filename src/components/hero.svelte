<script lang="ts">
  import Fa from "svelte-fa/src/fa.svelte";
  import { faGithub, faLinkedin } from "@fortawesome/free-brands-svg-icons";
  import { faEnvelope, faFilePdf } from "@fortawesome/free-regular-svg-icons";
</script>

<a id="hero">
  <div class="hero min-h-screen w-100" style="background-image: url(https://api.lorem.space/image/game?w=900&h=700);">
    <div class="hero-overlay bg-opacity-60" />
    <div class="hero-content text-center text-neutral-content">
      <div class="max-w-md glass rounded-box p-10 px-20">
        <h1 class="mb-5 text-5xl font-bold">Hello There!</h1>
        <h2 class="mb-5 text-4xl font-bold">I'm Thomas</h2>
        <span class="flex p-2">
          <a href="github.com" class="hover:bg-primary btn btn-circle mx-2 p-0"><Fa icon={faGithub} size="2.5x" /> </a>
          <a href="linkedin.com" class="hover:bg-primary btn btn-circle rounded-full mx-2 p-0"><Fa icon={faLinkedin} size="2.5x" /></a>
          <a href="email" class="hover:bg-primary btn btn-circle rounded-full mx-2 p-0"><Fa icon={faEnvelope} size="2.5x" /></a>
          <a href="resume" class="hover:bg-primary btn btn-circle mx-2 p-0"><Fa icon={faFilePdf} size="2.5x" /></a>
        </span>
      </div>
    </div>
  </div>
</a>
