<template>
  <div class="">
    <v-img :src="require(`@/assets/${image}`)" width="100%" height="200px"></v-img>
    <!-- <div class="borders"></div> -->
  </div>
</template>

<script lang="ts">
import Vue from 'vue';
import Component from 'vue-class-component';

@Component({
  name: 'StormImage',
  props: {
    image: String,
  },
})
export default class StormImage extends Vue {
}
</script>

<style scoped>
.borders {
  width: 100%;
  height: 150px;
  border: solid 8px black;
}
</style>
