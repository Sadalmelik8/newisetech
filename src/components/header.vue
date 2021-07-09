<template>
  <div class="hello">
    <div class="header">
      <h2>newisetech</h2>
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
  position: fixed;
  top: 0;
  border-bottom: 0.01rem #fff solid;

  .header {
    display: flex;
    width: 100vw;
    height: 3rem;
    align-items: center;
    justify-content: center;
    color: #fff;
    h2:hover{
      color red
    }
  }
}
</style>
