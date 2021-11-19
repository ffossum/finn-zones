<script context="module" lang="ts">
  export const prerender = true;
</script>

<script lang="ts">
  let selectedFloor = "3";
</script>

<svelte:head>
  <title>Home</title>
</svelte:head>

<section>
  <label for="floor-selector"> Floor </label>
  <select id="floor-selector" bind:value={selectedFloor}>
    <option value="3">3rd floor</option>
    <option value="5">5th floor</option>
  </select>

  {#if selectedFloor === "3"}
    <img src="3rd-floor.png" alt="3rd floor floorplan" />
  {:else if selectedFloor === "5"}
    <img src="5th-floor.png" alt="4th floor floorplan" />
  {/if}
</section>

<style>
  section {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    flex: 1;
  }

  img {
    filter: grayscale(1) opacity(0.5);
  }
</style>
