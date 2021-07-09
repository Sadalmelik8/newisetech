<template>
  <div class="home">
    <pageheader class="header"></pageheader>
    <pagemain class="main"></pagemain>
    <pagefooter class="footer"></pagefooter>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import pageheader from "@/components/header.vue"; // @ is an alias to /src
import pagefooter from "@/components/footer.vue"; // @ is an alias to /src
import pagemain from "@/components/main.vue"; // @ is an alias to /src

@Component({
  components: {
    pageheader,
    pagefooter,
    pagemain,
  },
})
export default class Home extends Vue {}
</script>
<style lang="stylus" scoped>
.home {
  .header {
  }

  .main {
  }

  .footer {
  }
}
</style>