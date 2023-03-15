<template>
  <div class="about">
    <h1>Learn</h1>
    <resources />
    <h3>We Run BTC</h3>
    <a href="https://werunbtc.com/" target="_blank"
      >Excellent curated getting started site</a
    >
    <h3>How do mneumonic seeds word? (12 or 24 seed words)</h3>
    <a href="https://www.youtube.com/watch?v=wWCIQFNf_8g" target="_blank"
      >Youtube Explanation</a
    >
    <p>
      <a
        href="https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki"
        target="_blank"
        >Bitcoin Improvement Proposal (BIP) 39</a
      >
      defines mneumonic seed words.
    </p>
    <p>
      There are
      <a
        href="https://github.com/bitcoin/bips/blob/master/bip-0039/english.txt"
        target="_blank"
        >2048 mneumonic seed words.</a
      >
    </p>
    <p>
      The seed words used for your recovery are input into a cryptographic hash
      along with a user-defined passphrase.
    </p>
    <p>
      This hash is then used to generate a private key, generally using
      <a
        href="https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki"
        target="_blank"
        >BIP32</a
      >
      methodology.
    </p>
    <p>
      <strong
        >Note: Don't select your own words, use hardware/software designed for
        the purpose.</strong
      >
    </p>
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
