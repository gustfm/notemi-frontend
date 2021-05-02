<template>
  <div class="sidebar">
    <div></div>
    <ul class="sidebar__menu">
      <SidebarItem :isTitle="true" text="Notes" />
      <SidebarItem text="School" />
      <SidebarItem text="Jobs" />
      <SidebarItem text="Freelas" />
      <SidebarItem text="Finances" />
    </ul>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

import SidebarItem from "./SidebarItem.vue";

@Component({
  components: {
    SidebarItem,
  },
})
export default class Sidebar extends Vue {}
</script>

<style lang="scss" scoped>
.sidebar {
  background-color: #1f1f1f;
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: flex-end;

  &__menu {
    width: 85%;
  }
}
</style>
