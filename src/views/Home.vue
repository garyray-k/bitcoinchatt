<template>
  <div class="home">
    <h2>
      Next Meeting: Bitcoin Board Game Night June 22nd @ 5pm <br />Location:
      <a href="https://goo.gl/maps/yQky74FiHniAZMht7" target="_blank"
        >College Park Church of Christ
      </a>
    </h2>
    <h3>
      Please RSVP with
      <a
        href="https://www.meetup.com/shenandoah-bitcoin-club/events/293824584/"
        target="_blank"
        >on Meetup.com</a
      >
      if you plan on attending.
    </h3>
    <h1>Shenandoah Bitcoin Club</h1>
    <p>Educating and collaborating on Bitcoin in the Shenandoah Valley.</p>
    <img alt="Bitcoin symbol" src="../assets/logo.png" class="center-fit" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Home",
});
</script>
<style scoped>
.center-fit {
  max-width: 100%;
  max-height: 100vh;
  margin: auto;
}
</style>
