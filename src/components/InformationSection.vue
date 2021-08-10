<template>
  <v-container>
    <v-row>
      <v-col cols="12" sm="6">
        <storm-image :image="'img/microphone.jpg'" />
      </v-col>
      <v-col cols="12" sm="6">
        <text-information
        :title="'Graba en nuestras instalaciones'"
        :body="`Highstorm records es una discográfica
         con espacio de creación musical propio y
         con un equipo: profesional, cercano y apasionado por el sonido.`"/>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12" sm="6">
        <storm-image :image="'img/videoclip.jpg'" />
      </v-col>
      <v-col cols="12" sm="6">
        <text-information
        :title="'Graba en nuestras instalaciones'"
        :body="`Highstorm records es una discográfica
         con espacio de creación musical propio y
         con un equipo: profesional, cercano y apasionado por el sonido.`"/>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12" sm="6">
        <storm-image :image="'img/storm_session.jpg'" />
      </v-col>
      <v-col cols="12" sm="6">
        <text-information
        :title="'Las storm sessions'"
        :body="`Las storm sessions son la perfecta combinacion de
         audio y videoo. Todo en nuestras instalaciones.`"/>
      </v-col>
    </v-row>
  </v-container>
</template>

<script lang="ts">
import Vue from 'vue';
import StormImage from '@/components/StormImage.vue';
import TextInformation from '@/components/TextInformation.vue';

export default Vue.extend({
  name: 'InformationSection',
  components: {
    StormImage,
    TextInformation,
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
