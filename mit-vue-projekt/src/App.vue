<template>
  <div class="container">
    <h1>Hi im Simon</h1>
    <h2>Frontend developer from Denmark</h2>
    <p>This portfolio is used to showcase my work.</p>
    <p>This portfolio is used to showcase my work.</p>
  </div>
  <div>
    <h2>hello</h2>
  </div>
</template>


<script>
import { colorBlack } from './assets/global/_background-color.scss';
import './assets/global.scss';

export default {
  mounted() {
    document.body.style.backgroundColor = colorBlack;
  },
}
</script>

<style lang="scss">
@import './assets/global.scss';

.container {
  background-color: black;
  color: white;
}

body {
  background-color: $color-black;
}
</style>