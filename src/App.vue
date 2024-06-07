<template>
 <div id="app">
  <h1>Calculator</h1>
  <Calculator />
 </div>
</template>

<script>
import Calculator from './main/SimpleCalculator';

export default {
  components: { Calculator }
};
</script>

<style>
  @font-face {
    font-family: 'RobotoMono';
    src: url("./fonts/RobotoMono-Thin.ttf");
  }

  * {
    font-family: 'RobotoMono', monospace;
  }

  body {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  #app {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;

    color: #fff;
    background: #0D1B2A;
  }
</style>