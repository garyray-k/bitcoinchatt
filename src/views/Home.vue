<template>
  <div class="home">
    <h2>
      Check out the meetup group
      <a href="https://www.meetup.com/shenandoah-bitcoin-club/" target="_blank"
        >on Meetup.com</a
      >
      to see when our next monthly meetup is.
    </h2>
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
