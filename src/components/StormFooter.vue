<template>
  <v-footer padless class="black">
    <v-col class="text-center white--text" cols="12">
      {{ new Date().getFullYear() }} — <strong>High Storm Records&#174;</strong>
    </v-col>
  </v-footer>
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
  name: 'StormFooter',
});
</script>

<style scoped>
</style>
