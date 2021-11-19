<script lang="ts">
</script>

<div class="floorplan">
  <img src="5th-floor.png" alt="5th floor floorplan" />

  <div class="grensen">
    <div class="zone collab-high zone-5e" data-zone="5e" />
    <div class="zone collab-high zone-5d" data-zone="5d" />
    <div class="zone collab-high zone-5a" data-zone="5a" />
    <div class="zone collab-high zone-5b" data-zone="5b" />
    <div class="zone collab-high zone-5c" data-zone="5c" />
  </div>
</div>

<style>
  .floorplan {
    position: relative;
  }

  .grensen {
    top: 0;
    left: 0;
    position: absolute;
  }

  .zone {
    position: absolute;
    background-color: rgba(100, 100, 100, 0.5);

    width: 6rem;
    height: 6rem;

    top: 1rem;
    left: 1rem;

    border-radius: 0.5rem;

    text-transform: uppercase;

    display: flex;
    justify-content: flex-start;
    align-items: flex-start;

    color: var(--pure-white);
    font-size: 100%;
    font-weight: bold;
    text-shadow: 0 0 1em #000a;
  }
  .zone::after {
    margin-top: 0.25em;
    margin-left: 0.25em;
    content: attr(data-zone);
    background-color: #0005;
    padding: 0.25em;
    border-radius: 0.25em;
  }

  .zone.collab-low {
    background-color: rgba(16, 187, 16, 0.5);
  }
  .zone.collab-medium {
    background-color: rgba(50, 60, 200, 0.5);
  }
  .zone.collab-high {
    background-color: rgba(200, 50, 50, 0.5);
  }

  .zone-5e {
    height: 4rem;
    top: 9rem;
    left: 74rem;
    width: 5rem;
  }

  .zone-5d {
    height: 5rem;
    top: 9rem;
    left: 81rem;
    width: 7rem;
  }

  .zone-5a {
    height: 5rem;
    top: 17rem;
    left: 68rem;
    width: 4rem;
  }

  .zone-5b {
    height: 5rem;
    top: 17rem;
    left: 73rem;
    width: 6rem;
  }

  .zone-5c {
    height: 5rem;
    top: 18rem;
    left: 81rem;
    width: 7rem;
  }

  img {
    filter: grayscale(1) opacity(0.5);
  }
</style>
