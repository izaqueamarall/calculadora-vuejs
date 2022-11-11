<template>
  <div class="card-calculator">
    <div class="display">
      <p>DISPLAY</p>
    </div>
    <div class="calculator-panel">
      <div><button>7</button></div>
      <div><button>8</button></div>
      <div><button>9</button></div>
      <div><button>+</button></div>
      <div><button>4</button></div>
      <div><button>5</button></div>
      <div><button>6</button></div>
      <div><button>-</button></div>
      <div><button>1</button></div>
      <div><button>2</button></div>
      <div><button>3</button></div>
      <div><button>x</button></div>
      <div><button>0</button></div>
      <div><button>,</button></div>
      <div><button>=</button></div>
      <div><button>/</button></div>
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
.display > p {
    color: white;
    text-align: center;
}
.calculator-panel {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
