<template>
  <v-container>
    <v-row justify="center">
      <v-col cols="12" sm="6" md="4">
        <div class="d-flex flex-column">
          <v-btn class="white--text" color="#C13584">
            <a
              href="https://www.instagram.com/highstormrecords/"
              target="_blank"
            >
              Contactanos por instagram
            </a>
          </v-btn>
          <div class="d-flex justify-center align-center">
            <div class="storm-divider black"></div>
            <div class="px-2">o</div>
            <div class="storm-divider black"></div>
          </div>
          <v-btn class="white--text" color="black"
            >highstormrecords@gmail.com</v-btn
          >
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class Buttons extends Vue {}
</script>

<style scoped>
.storm-divider {
  width: 100%;
  height: 1px;
}
a:link {
  text-decoration: inherit;
  color: inherit;
  cursor: pointer;
}

a:visited {
  text-decoration: inherit;
  color: inherit;
  cursor: pointer;
}
</style>
