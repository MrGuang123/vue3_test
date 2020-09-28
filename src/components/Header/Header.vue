<template>
  <div class="header"></div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component'

@Options({})
export default class Header extends Vue {}
</script>
<style lang="scss" scoped>
.header {
  width: 100%;
  height: 60px;
  flex-basis: 60px;
  background: #f00;
}
</style>
