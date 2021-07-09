<template>
  <div class="hello">
    <div class="footer">
      <img src="../assets/material/bg1.png" alt="" />
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class HelloWorld extends Vue {}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">
.hello {
  // display: flex;
  // background-image: url('../assets/material/bg1.png');
  // background-repeat: no-repeat;
  // background-size: cover;
  // background-position-x: center;
  // width: 100vw;
  // background: #eee;
  // height: 10rem;
  // justify-content: center;
  .footer {
    img {
      width: 100%;
    }

    // background-color: #f7fbfd;
  }
}
</style>
