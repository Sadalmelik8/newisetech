<template>
  <div id="app" :style="{ height: appHeight + 'px' }">
    <router-view></router-view>
  </div>
</template>
<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component
export default class App extends Vue {
  private appHeight: number = 0;

  private created() {
    this.appHeight = parseInt(localStorage.getItem("clientHeight")!);

    // if(performance.navigation.type === 1) {
    //     this.$store.commit('setIsTimer');
    //     const refreshToken: Login = new Login();
    //     refreshToken.setRefreshToken();
    // }
    // sessionStorage.clear();
    // localStorage.removeItem("selectMchId");
    // if (localStorage.getItem("menus")) {
    //     const menus = JSON.parse(localStorage.getItem("menus")!);

    //     const resourceCodes = new DeepLoop().getResources(menus);
    //     console.log(resourceCodes);
    //     this.$store.commit("setResourceCodes", resourceCodes);
    // }
  }
}
</script>
<style lang="stylus">
* {
  padding: 0;
  margin: 0;
  border: none;
  box-sizing: border-box;
}
</style>
