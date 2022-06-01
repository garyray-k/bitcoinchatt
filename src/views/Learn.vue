<template>
  <div class="about">
    <h1>Learn</h1>
    <resources />
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
