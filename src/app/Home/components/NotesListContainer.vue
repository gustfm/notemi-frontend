<template>
  <div class="notes-list__container">
    <NotesList />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

import NotesList from "./NotesList.vue";

@Component({
  components: {
    NotesList,
  },
})
export default class NotesListContainer extends Vue {}
</script>

<style lang="scss" scoped>
.notes-list__container {
  background-color: #282828;
  height: 100vh;
}
</style>
