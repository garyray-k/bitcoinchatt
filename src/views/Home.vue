<template>
  <div class="home">
    <h2>
      Next Meeting: June 3rd, 2022 at 7pm. Location:
      <a
        href="https://www.villagesquarerestaurant.com/"
        target="_blank"
        class="ml-md-auto"
      >
        Village Square</a
      >
    </h2>
    <h3>Please RSVP with gary@codechief.dev if you plan on attending.</h3>
    <h1>Shenandoah Bitcoin Club</h1>
    <p>Educating an collaborating on Bitcoin in the Shenandoah Valley.</p>
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
