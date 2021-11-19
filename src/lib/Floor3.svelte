<script lang="ts">
</script>

<div class="floorplan">
  <img src="3rd-floor.png" alt="3rd floor floorplan" />

  <div class="hoyesterett">
    <div class="zone collab-low zone-3p" data-zone="3p" />
    <div class="zone collab-low zone-3o" data-zone="3o" />
    <div class="zone collab-low zone-3n" data-zone="3n" />
    <div class="zone collab-low zone-3m" data-zone="3m" />
    <div class="zone collab-low zone-3s" data-zone="3s" />
    <div class="zone collab-low zone-3r" data-zone="3r" />
    <div class="zone collab-low zone-3q" data-zone="3q" />

    <div class="zone collab-medium zone-3l" data-zone="3l" />
    <div class="zone collab-medium zone-3k" data-zone="3k" />
    <div class="zone collab-medium zone-3j" data-zone="3j" />
    <div class="zone collab-medium zone-3i" data-zone="3i" />
    <div class="zone collab-medium zone-3h" data-zone="3h" />
    <div class="zone collab-medium zone-3g" data-zone="3g" />
  </div>

  <div class="grensen">
    <div class="zone collab-high zone-3f" data-zone="3f" />
    <div class="zone collab-high zone-3e" data-zone="3e" />
    <div class="zone collab-high zone-3d" data-zone="3d" />
    <div class="zone collab-high zone-3a" data-zone="3a" />
    <div class="zone collab-high zone-3b" data-zone="3b" />
    <div class="zone collab-high zone-3c" data-zone="3c" />
  </div>
</div>

<style>
  .floorplan {
    position: relative;
  }

  .hoyesterett,
  .grensen {
    top: 0;
    left: 0;
    position: absolute;
  }

  .hoyesterett {
    transform: rotate(-4.5deg);
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

  .zone-3p {
    top: 9rem;
    width: 5rem;
    left: 2rem;
  }
  .zone-3o {
    height: 4rem;
    top: 12rem;
    left: 8rem;
  }
  .zone-3n {
    height: 7rem;
    top: 9rem;
    left: 15rem;
    width: 4rem;
  }
  .zone-3m {
    height: 7rem;
    top: 9rem;
    left: 21rem;
    width: 4rem;
  }
  .zone-3l {
    height: 4rem;
    top: 12rem;
    left: 26rem;
    width: 8rem;
  }
  .zone-3k {
    height: 4rem;
    top: 12rem;
    left: 35rem;
    width: 4rem;
  }
  .zone-3j {
    height: 7rem;
    top: 9rem;
    left: 41rem;
    width: 4rem;
  }

  .zone-3s {
    height: 4rem;
    top: 23rem;
    left: 5rem;
    width: 7rem;
  }
  .zone-3r {
    height: 7rem;
    top: 23rem;
    left: 14rem;
    width: 4rem;
  }
  .zone-3q {
    height: 7rem;
    top: 23rem;
    left: 20rem;
    width: 4rem;
  }
  .zone-3i {
    height: 5rem;
    top: 21rem;
    left: 25rem;
    width: 8rem;
  }

  .zone-3h {
    height: 4rem;
    top: 22rem;
    left: 34rem;
    width: 4rem;
  }

  .zone-3g {
    height: 4rem;
    top: 22rem;
    left: 40rem;
    width: 10rem;
  }

  .zone-3f {
    height: 4rem;
    top: 9rem;
    left: 66rem;
    width: 4rem;
  }

  .zone-3e {
    height: 4rem;
    top: 9rem;
    left: 74rem;
    width: 5rem;
  }

  .zone-3d {
    height: 5rem;
    top: 9rem;
    left: 81rem;
    width: 7rem;
  }

  .zone-3d {
    height: 5rem;
    top: 9rem;
    left: 81rem;
    width: 7rem;
  }

  .zone-3a {
    height: 5rem;
    top: 17rem;
    left: 66rem;
    width: 7rem;
  }

  .zone-3b {
    height: 5rem;
    top: 17rem;
    left: 74rem;
    width: 5rem;
  }

  .zone-3c {
    height: 5rem;
    top: 18rem;
    left: 81rem;
    width: 7rem;
  }

  img {
    filter: grayscale(1) opacity(0.5);
  }
</style>
