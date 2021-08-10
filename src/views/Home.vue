<template>
<div class=" d-flex flex-column justify-center">
  <storm-header />
  <h2 class="text-center text-h2">Creadores de musica urbana</h2>
  <!-- Check more info about typography here: https://vuetifyjs.com/en/styles/text-and-typography -->
  <information-section />
</div>
</template>

<script lang="ts">
import Vue from 'vue';
import StormHeader from '../components/StormHeader.vue';
import InformationSection from '../components/InformationSection.vue';

export default Vue.extend({
  name: 'Home',

  components: {
    StormHeader,
    InformationSection,
  },
});
</script>
