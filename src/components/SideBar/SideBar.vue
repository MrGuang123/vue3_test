<template>
  <div class="side-bar"></div>
</template>
<script lang="ts">
import { Options, Vue } from 'vue-class-component'

@Options({})
export default class SideBar extends Vue {}
</script>
<style lang="scss" scoped>
.side-bar {
  width: 240px;
  flex-basis: 240px;
  height: 100%;
  overflow-x: hidden;
  overflow-y: auto;
  background: #00f;
}
</style>
