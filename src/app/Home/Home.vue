<template>
  <div class="app">
    <Sidebar />
    <div>a</div>
    <div>b</div>
    <!-- <NotesListContainer /> -->
    <!-- <NoteContainer /> -->
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

import Sidebar from "@/components/Sidebar.vue";

@Component({
  components: {
    Sidebar,
  },
})
export default class Home extends Vue {}
</script>

<style lang="scss" scoped>
.app {
  display: grid;
  grid-template-columns: 240px 380px 1fr;
}
</style>