<template>
  <div class="side-bar">
    <slot name="title"></slot>
    <ul class="menu-wrap">
      <li class="menu-item">
        <i class="iconfont iconadjust"></i>
        <span>文档</span>
      </li>
    </ul>
  </div>
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
}
</style>
