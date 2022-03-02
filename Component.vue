<template>
  <div @click="selectTab">hello</div>
</template>

<script lang="ts">
import Component from "vue-class-component";

@Component
export default class Comp extends Vue {
  selectTab() {
    this.$emit("select", 1);
  }
}
</script>
