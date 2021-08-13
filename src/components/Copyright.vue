<template>
    <div class="text-center">
      {{ new Date().getFullYear() }} — <strong>High Storm Records&#174;</strong>
    </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component({
  name: 'Copyright',
})
export default class Copyright extends Vue {

}
</script>

<style scoped>

</style>
