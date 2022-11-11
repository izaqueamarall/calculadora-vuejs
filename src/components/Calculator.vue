<template>
  <div class="card-calculator">
    <div class="display">
      <p>TESTE</p>
    </div>
    <div class="calculator-panel">
      <div><button>7</button></div>
      <div><button>8</button></div>
      <div><button>9</button></div>
      <div><button>4</button></div>
      <div><button>5</button></div>
      <div><button>6</button></div>
      <div><button>1</button></div>
      <div><button>2</button></div>
      <div><button>3</button></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CalculatorCard",
};
</script>

<style scoped>
.card-calculator {
}
.display {
background-color: black;
}
.calculator-panel {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
