<template>
  <div class="app">
    <Sidebar />
    <NotesListContainer />
    <NoteContainer />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

import Sidebar from "./components/Sidebar.vue";
import NotesListContainer from "./components/NotesListContainer.vue";
import NoteContainer from "./components/NoteContainer.vue";

@Component({
  components: {
    Sidebar,
    NotesListContainer,
    NoteContainer,
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
