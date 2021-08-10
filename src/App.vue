<template>
  <v-app>
    <v-main>
      <router-view/>
    </v-main>
  <storm-footer />
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue';
import StormFooter from '@/components/StormFooter.vue';

export default Vue.extend({
  name: 'App',
  components: {
    StormFooter,
  },

  data: () => ({
    //
  }),
});
</script>
