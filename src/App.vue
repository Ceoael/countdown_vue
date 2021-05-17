<template>
  <countdown-timer-builder></countdown-timer-builder>
</template>

<script>
  import CountdownTimerBuilder from './pages/CountdownTimerBuilder.vue';

  export default {
    components : {
      CountdownTimerBuilder
    }
  }
</script>

<style>
  * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

  body {
    background-color: #100E1D;
  }
</style>
