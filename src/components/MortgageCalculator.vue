<script setup>
import { ref } from "vue";
</script>

<template>
  <h3>Mortgage Calculator</h3>

  <div class="mortgageCalcContainer">
    <div class="containerRow">
      <label for="homeValue">Home Value</label>
      <input name="homeValue" type="text" />
    </div>
    <div class="containerRow">
      <label for="homeValue">Home Value</label>
      <input name="homeValue" type="text" />
    </div>
  </div>
</template>

<style scoped>
label {
  padding-right: 0.75rem;
}
.mortgageCalcContainer {
  display: flex;
  flex-direction: column;
}

.containerRow {
  margin-bottom: 0.75rem;
}
</style>
