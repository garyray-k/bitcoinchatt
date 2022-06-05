<template>
  <div class="about">
    <h1>Learn</h1>
    <resources />
    <h3>How do mneumonic seeds word? (12 or 24 seed words)</h3>
    <a href="https://www.youtube.com/watch?v=wWCIQFNf_8g" target="_blank"
      >Youtube Explanation</a
    >
    <p>Bitcoin Improvement Proposal (BIP) 39 defines mneumonic seed words.</p>
    <p>There are 2048 mneumonic seed words.</p>
    <p>
      The seed words used for your recovery are input into a cryptographic hash
      along with a user-defined passphrase.
    </p>
    <p>This hash is then used to generate a private key.</p>
  </div>
</template>
<script lang="ts">
import { defineComponent } from "vue";
import Resources from "@/components/Resources.vue"; // @ is an alias to /src

export default defineComponent({
  name: "Learn",
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
