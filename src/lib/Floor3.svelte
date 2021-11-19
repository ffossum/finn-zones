<script lang="ts">
</script>

<div class="floorplan">
  <img src="3rd-floor.png" alt="3rd floor floorplan" />

  <div class="hoyesterett">
    <div class="zone zone-3p" />
    <div class="zone zone-3o" />
    <div class="zone zone-3n" />
    <div class="zone zone-3m" />
    <div class="zone zone-3l" />
    <div class="zone zone-3k" />
    <div class="zone zone-3j" />
    <div class="zone zone-3s" />
    <div class="zone zone-3r" />
    <div class="zone zone-3q" />
    <div class="zone zone-3i" />
    <div class="zone zone-3h" />
    <div class="zone zone-3g" />
  </div>
  <div class="grensen">
    <div class="zone zone-3f" />
    <div class="zone zone-3e" />
    <div class="zone zone-3d" />
    <div class="zone zone-3a" />
    <div class="zone zone-3b" />
    <div class="zone zone-3c" />
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
    background-color: rgba(50, 60, 200, 0.5);

    width: 6rem;
    height: 6rem;

    top: 1rem;
    left: 1rem;

    border-radius: 0.5rem;
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
