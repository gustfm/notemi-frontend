<template>
  <ul class="notes-list">
    <!-- <NotesListItem isTitle title="Auuuuuuuuuuuuu" /> -->
  </ul>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

// import NotesListItem from "./SidebarItem.vue";

@Component({
  components: {
    // NotesListItem,
  },
})
export default class NotesList extends Vue {}
</script>

<style lang="scss" scoped>
.notes-list {
  background-color: #282828;
  height: 100vh;
}
</style>
