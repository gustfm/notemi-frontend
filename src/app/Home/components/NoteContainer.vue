<template>
  <div class="note__container">
    note__container
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component({})
export default class NoteContainer extends Vue {}
</script>

<style lang="scss" scoped>
.note__container {
  background-color: #323232;
  height: 100vh;
}
</style>
