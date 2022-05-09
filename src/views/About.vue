<template>
  <div class="about">
    <h1>About</h1>
    <resources />
    <p>Run by Gary Krause, a software engineer and a bitcoin enthusiast.</p>
    <p>
      Meeting occuring monthly as various lcoations around the Winchester area.
    </p>
    <p>If you're interested in more information, please contact me.</p>
    <h3>Contact</h3>
    <ul>
      <li>
        <a href="mailto:gary@codechief.dev" class="ml-md-auto"
          >gary@codechief.dev</a
        >
      </li>
      <li>
        <a href="https://codechief.dev" target="_blank" class="ml-md-auto"
          >Code Chief LLC</a
        >
      </li>
    </ul>
  </div>
</template>
<script lang="ts">
import { defineComponent } from "vue";
import Resources from "@/components/Resources.vue"; // @ is an alias to /src

export default defineComponent({
  name: "About",
  components: {
    Resources,
  },
});
</script>
