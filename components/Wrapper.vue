<template>
  <h1>Hi, I'm wrapping a third party library</h1>
</template>

<script>
import gallery from "~/vendor/third-party-lib.js";

export default {
  name: "Wrapper",

  mounted() {
    gallery();
  }
};
</script>