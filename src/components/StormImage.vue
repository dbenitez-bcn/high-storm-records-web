<template>
  <div>
    <div class="bg"></div>
    <div class="borders m-2"></div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'StormImage',
});
</script>

<style scoped>
.borders {
  width: 100%;
  height: 200px;
  border: solid 8px black;
}
</style>
