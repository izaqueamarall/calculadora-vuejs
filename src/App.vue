<template>
  <div class="main-card">
    <h1>Pequeno projeto de calculadora em desenvolvimento...</h1>
    <CalculatorCard />
  </div>
</template>

<script>
import CalculatorCard from "./components/Calculator.vue";
export default {
  data() {
    return {};
  },
  components: {
    CalculatorCard,
  },
};
</script>

<style>
.main-card {
  width: 100vw;
  height: 100vh;
  background: #ffffff;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.main-card > h1 {
  font-family: 'Courier New', Courier, monospace;
}
</style>
