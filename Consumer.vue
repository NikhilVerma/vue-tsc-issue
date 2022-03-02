<template>
  <Component @select="selectTab" />
</template>

<script lang="ts">
import Component from "vue-class-component";

@Component({
  components: {
    Component,
  },
})
export default class Consumer extends Vue {
  selectTab(value: number) {
    console.log(value);
  }
}
</script>
