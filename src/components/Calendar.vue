<template>
  <div class="calendar"></div>
</template>

<script>
import { produce } from "../database";

export default {
  name: "Calendar",
  async mounted() {
    console.log(await produce);
  },
};
</script>

<style scoped lang="scss"></style>
