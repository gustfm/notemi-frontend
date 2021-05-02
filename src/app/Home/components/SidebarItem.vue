<template>
  <div>
    <i></i>
    <p
      :class="{ 'font-medium': isTitle, 'text-sm': !isTitle }"
      class="notes__list-item text-white py-2"
    >
      {{ text }}
    </p>
  </div>
</template>

<script lang="ts">
import { Vue, Component, Prop } from "vue-property-decorator";

@Component({})
export default class SidebarItem extends Vue {
  @Prop({ default: false }) public isTitle: boolean;
  @Prop() public text: string;
}
</script>

<style lang="scss"></style>
