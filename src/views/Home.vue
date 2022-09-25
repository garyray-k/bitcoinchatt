<template>
  x
  <div class="home">
    <h2>
      Next Meeting: October 13, 2022 @ 7pm Location: Cafe Del Sol - Winchester
    </h2>
    <h3>Please RSVP with gary@codechief.dev if you plan on attending.</h3>
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
