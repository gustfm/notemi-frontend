<template>
  <div class="sidebar">
    <div>Private</div>
    <div class="sidebar__menu"></div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component({})
export default class Sidebar extends Vue {}
</script>

<style lang="scss" scoped>
.sidebar {
  background-color: #1f1f1f;
//   width: 280px;
  height: 100vh;
}
</style>
