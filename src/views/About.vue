<template>
  <div class="about">
    <h1>About</h1>
    <p>Run by Gary Krause, a software engineer and a bitcoin enthusiast.</p>
    <p>
      Meeting occuring monthly as various lcoations around the Winchester area.
    </p>
    <p>If you're interested in more information, please contact me.</p>
    <resources />
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
      <li>
        <a
          href="https://www.linkedin.com/in/garyray-k/"
          target="_blank"
          class="ml-md-auto"
          >LinkedIn</a
        >
      </li>
    </ul>
    <h4>
      <a
        href="https://github.com/CodeChiefDotDev/shenandoahbitcoinclub/issues"
        target="_blank"
        class="ml-md-auto"
      >
        See an Error on this site?</a
      >
    </h4>
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
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
