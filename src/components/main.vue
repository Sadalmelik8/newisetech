<template>
  <div class="hello">
    <div class="propaganda">
      <!-- <img src="../assets/material/bg.png" alt="" /> -->
    </div>
    <div class="main">
      <div class="tab1">
        <img src="../assets/material/tab1.png" alt="" />
        <div class="chapter">1</div>
        <div class="chapter">2</div>
        <div class="chapter">3</div>
        <div class="chapter">4</div>
      </div>
      <div class="tab2">
        <img src="../assets/material/tab2.png" alt="" />
      </div>
      <div class="tab3">
        <img src="../assets/material/tab3.png" alt="" />
      </div>
      <div class="tab5">
        <img src="../assets/material/tab5.png" alt="" />
      </div>
      <div class="tab4">
        <img src="../assets/material/tab4.png" alt="" />
      </div>
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
  .propaganda {
    width: 100%;
    height: 100vh;
    background-image: url('../assets/material/bg.png');
    background-position: center;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: cover;

    img {
      width: 100%;
    }
  }

  .main {
    .tab1 {
      img {
        width: 100%;
      }

      .chapter {
        color: white;
      }
    }

    .tab2 {
      img {
        width: 100%;
        // border 5px red solid
      }

      img:hover {
        // border-radius: 2%;
        // -webkit-box-shadow: 0.5rem rgba(0, 113, 241, 1);
      }
    }

    .tab3 {
      img {
        width: 100%;
      }
    }

    .tab4 {
      img {
        width: 100%;
      }
    }

    .tab5 {
      img {
        width: 100%;
      }
    }
  }
}
</style>
