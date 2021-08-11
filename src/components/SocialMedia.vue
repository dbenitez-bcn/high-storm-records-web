<template>
<div>
    <div
        class="d-flex align-center"
        v-for="(item, i) in socialMedias"
        :key="i"
        >
        <v-icon color="white">mdi-{{item.icon}}</v-icon>
        <a class="nostyle ml-1" :href="item.link" target="_blank">{{item.title}}</a>
    </div>
</div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component({
  name: 'SocialMedia',
})
export default class SocialMedia extends Vue {
    private socialMedias = [
      {
        icon: 'instagram',
        title: '/highstormrecords',
        link: 'https://www.instagram.com/highstormrecords/',
      },
      {
        icon: 'youtube',
        title: 'HighStormRecords',
        link: 'https://www.youtube.com/channel/UCIoxczOpGkMuzRqM7RciJSw',
      },
    ];
}
</script>

<style scoped>
a.nostyle:link {
    text-decoration: inherit;
    color: inherit;
    cursor: pointer;
}

a.nostyle:visited {
    text-decoration: inherit;
    color: inherit;
    cursor: pointer;
}

</style>
