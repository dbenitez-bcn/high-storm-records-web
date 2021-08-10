<template>
    <div>
        <h2 class="text-center text-sm-left">{{title}}</h2>
        <p class="text-justify">{{body}}</p>
    </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component({
  name: 'TextInformation',
  props: {
    title: String,
    body: String,
  },
})
export default class TextInformation extends Vue {

}
</script>

<style scoped>

</style>
