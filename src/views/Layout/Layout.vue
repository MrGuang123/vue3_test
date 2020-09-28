<template>
  <div class="layout">
    <SideBar />
    <div class="content-wrap">
      <Header></Header>
      <div class="content">
        <router-view></router-view>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
// import Vue from 'vue'
import classCom, { Vue } from 'vue-class-component'
import { Header, SideBar } from '../../components/index'

// @Component({
//   components: {
//     Header,
//     SideBar
//   }
// })
// @Component({})
export default class Layout extends Vue {
  mounted() {
    console.log(classCom)
  }
  components: {
    Header
    SideBar
  }
}
</script>
<style lang="scss" scoped>
.layout {
  width: 100vw;
  height: 100vh;
  display: flex;
}
.content-wrap {
  flex: 1;
  display: flex;
  flex-direction: column;
  .content {
    flex: 1;
    background: #0f0;
  }
}
</style>
