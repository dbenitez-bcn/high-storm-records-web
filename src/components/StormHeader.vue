<template>
  <div :class="getClassBasedOnBreakpoint">
  </div>
</template>

<script lang="ts">
import Vue from 'vue';
import Component from 'vue-class-component';

@Component({
  name: 'StormHeader',
  props: {
    image: String,
  },
})
export default class StormHeader extends Vue {
  get getClassBasedOnBreakpoint(): string {
    return `storm-header-${this.$vuetify.breakpoint.name}`;
  }
}
</script>

<style lang="scss" scoped>
.storm-header {
  width: 100%;
  background-image: url("../assets/img/headerBg.jpg");
  background-repeat: no-repeat;
  clip-path: polygon(0 0, 100% 0, 100% 82%, 0 100%);

  &-xs {
    @extend .storm-header;
    height: 180px;
    background-size: 122%;
    background-position: 6% 33%;
  }

  &-sm {
    @extend .storm-header;
    height: 256px;
    background-size: 122%;
    background-position: 6% 33%;
  }

  &-md {
    @extend .storm-header;
    height: 50vh;
    background-size: 142%;
    background-position: 30% 33%;
  }

  &-lg {
    @extend .storm-header;
    height: 90vh;
    background-size: 110%;
    background-position: 6% 33%;
  }

  &-xl {
    @extend .storm-header;
    height: 90vh;
    background-size: 110%;
    background-position: 6% 33%;
  }
}
</style>
