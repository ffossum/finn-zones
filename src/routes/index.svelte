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
  <ul>
    <li>
      <label for="3rd-floor-button">
        <input type="radio" id="3rd-floor-button" bind:group={selectedFloor} value="3" />
        3rd floor
      </label>
    </li>
    <li>
      <label for="5th-floor-button">
        <input type="radio" id="5th-floor-button" bind:group={selectedFloor} value="5" />
        5th floor
      </label>
    </li>
  </ul>

  {#if selectedFloor === "3"}
    <img src="3rd-floor.png" alt="3rd floor floorplan" />
  {:else if selectedFloor === "5"}
    <img src="5th-floor.png" alt="5th floor floorplan" />
  {/if}
</section>

<style>
  ul {
    list-style: none;
    padding-left: 0;

    display: flex;
  }
  li {
    margin-left: 0.5em;
    margin-right: 0.5em;
  }
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
