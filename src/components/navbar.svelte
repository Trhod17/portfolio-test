<script lang="ts">
  import NavBtn from "./navbtn.svelte";
</script>

<header class="navbar bg-neutral fixed z-50">
  <div class="navbar-start">
    <div class="dropdown">
      <!-- svelte-ignore a11y-label-has-associated-control -->
      <label tabindex="0" class="btn btn-ghost lg:hidden">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"
          ><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16" /></svg
        >
      </label>
      <ul tabindex="0" class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52">
        <NavBtn path="#hero" name="Home" />
        <NavBtn path="#aboutme" name="About Me" />
        <NavBtn path="#work" name="Work Experience" />
        <NavBtn path="#projects" name="Projects" />
        <NavBtn path="#tech" name="Skills" />
      </ul>
    </div>
    <ul class="menu menu-horizontal p-0">
      <NavBtn path="#hero" name="Home" />
      <NavBtn path="#aboutme" name="About Me" />
      <NavBtn path="#work" name="Work Experience" />
      <NavBtn path="#projects" name="Projects" />
      <NavBtn path="#tech" name="Skills" />
    </ul>
  </div>
  <div class="navbar-center hidden lg:flex" />
</header>
