<template>
  <div class="main-card">
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
}
</style>
