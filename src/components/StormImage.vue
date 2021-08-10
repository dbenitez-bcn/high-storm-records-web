<template>
  <div>
    <div class="bg"></div>
    <div class="borders"></div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
  name: 'StormImage',
});
</script>

<style scoped>
.borders {
  width: 100%;
  height: 150px;
  border: solid 8px black;
}
</style>
