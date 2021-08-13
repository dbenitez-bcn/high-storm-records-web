<template>
  <v-footer padless class="black white--text">
    <v-container>
      <v-row>
        <v-col cols="12" sm="4">
          <social-media />
        </v-col>
        <v-col class="order-sm-last" cols="12" sm="4">
          <contact class="order-sm-last" />
        </v-col>
        <v-col cols="12" sm="4" align-self="center">
          <copyright />
        </v-col>
      </v-row>
    </v-container>
  </v-footer>
</template>

<script lang="ts">
import Vue from 'vue';
import SocialMedia from '@/components/SocialMedia.vue';
import Copyright from '@/components/Copyright.vue';
import Contact from '@/components/Contact.vue';

export default Vue.extend({
  name: 'StormFooter',
  components: {
    SocialMedia,
    Copyright,
    Contact,
  },
});
</script>

<style scoped>
</style>
