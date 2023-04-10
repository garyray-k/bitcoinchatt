<template>
  <div class="about">
    <h1>Support the Club</h1>
    <ul>
      <li>
        <a
          href="https://river.com/signup?r=JRVL66TO"
          target="_blank"
          class="ml-md-auto"
          >River Referral Link (BTC only Exchange/Company)</a
        >
        <p>Our recommended exchange.</p>
      </li>
      <li>
        <a
          href="https://www.swanbitcoin.com/garykrause"
          target="_blank"
          class="ml-md-auto"
          >Swan Bitcoin Referral Link (BTC only Exchange)</a
        >
      </li>
    </ul>
    <h3>One on One Bitcoin Support</h3>
    <p>Please contact gary@codechief.dev to discuss.</p>
  </div>
</template>
<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Support",
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
