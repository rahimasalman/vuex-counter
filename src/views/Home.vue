<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <Counter />
    <Buttons />
    <CounterSquared />
    <ColorCode />
  </div>
</template>

<script>
import Counter from "../components/Counter";
import CounterSquared from "../components/CounterSquared";
import ColorCode from "../components/ColorCode";
import Buttons from "../components/Buttons";
export default {
  name: "Home",
  components: {
    Counter,
    CounterSquared,
    ColorCode,
    Buttons,
  },
};
</script>
<style scoped>
div {
  margin-bottom: 20px;
}
</style>
