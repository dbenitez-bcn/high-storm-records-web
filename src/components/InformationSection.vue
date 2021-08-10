<template>
  <v-container>
    <v-row>
      <v-col cols="12" sm="6">
        <storm-image />
      </v-col>
      <v-col cols="12" sm="6">
        <div class="testerino"></div>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12" sm="6">
        <div class="testerino"></div>
      </v-col>
      <v-col cols="12" sm="6">
        <div class="testerino"></div>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12" sm="6">
        <div class="testerino"></div>
      </v-col>
      <v-col cols="12" sm="6">
        <div class="testerino"></div>
      </v-col>
    </v-row>
  </v-container>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import StormImage from '@/components/StormImage.vue';

export default defineComponent({
  name: 'InformationSection',
  components: {
    StormImage,
  },
});
</script>

<style scoped>
.testerino {
  width: 100%;
  height: 150px;
  background-color: red;
}
</style>
