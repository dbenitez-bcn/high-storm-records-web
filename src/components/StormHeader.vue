<template>
    <div class="storm-header">
        <!-- <div class="triangle white"></div> -->
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'StormHeader',
});
</script>

<style scoped>
.storm-header {
    width: 100%;
    height: 200px;
    background-image: url('../assets/img/headerBg.jpg');
    background-repeat: no-repeat;
    background-size: 122%;
    background-position: 6% 28%;
}
.triangle {
width: 0;
height: 0;
border-style: solid;
border-width: 0 0 316px 330px;
border-color: transparent transparent #007bff transparent;
}
</style>
