<script lang="ts">
  export let name: string;
  export let description: string;
  export let badges: string[];
</script>

<div class="card w-full bg-base-100 shadow-md shadow-secondary border-primary border-2 p-0">
  <div class="card-body text-center w-full p-1 py-10">
    <h2 class="card-title text-center mx-auto">{name}</h2>
    <p class="mx-10 px-10">{description}</p>
    <div class="card-actions justify-center w-full">
      {#each badges as badge}
        <div class="badge badge-info text-info-content">{badge}</div>
      {/each}
    </div>
  </div>
</div>
