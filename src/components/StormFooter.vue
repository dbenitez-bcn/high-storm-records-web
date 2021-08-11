<template>
  <v-footer padless class="black white--text">
    <social-media />
    <v-col class="text-center" cols="12">
      {{ new Date().getFullYear() }} — <strong>High Storm Records&#174;</strong>
    </v-col>
  </v-footer>
</template>

<script lang="ts">
import Vue from 'vue';
import SocialMedia from '@/components/SocialMedia.vue';

export default Vue.extend({
  name: 'StormFooter',
  components: {
    SocialMedia,
  },
});
</script>

<style scoped>
</style>
