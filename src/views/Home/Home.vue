<template>
  <div class="home">
    <h1>home</h1>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component'

@Options({
  components: {}
})
export default class Home extends Vue {}
</script>
<style lang="scss" scoped>
.home {
  width: 100%;
  height: 100%;
  background: #0f0;
}
</style>
