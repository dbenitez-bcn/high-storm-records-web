<template>
<div>
    <div
        class="d-flex align-center"
        v-for="(item, i) in contacts"
        :key="i"
        >
        <v-icon color="white">mdi-{{item.icon}}</v-icon>
        <span class="ml-1">{{item.title}}</span>
    </div>
</div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component({
  name: 'Contact',
})
export default class SocialMedia extends Vue {
    private contacts = [
      {
        icon: 'email',
        title: 'highstormrecords@gmail.com',
      },
      {
        icon: 'phone',
        title: '+34 648 70 37 34',
      },
    ];
}
</script>

<style scoped>
</style>
