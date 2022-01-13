<script setup>
import { ref } from "vue";
</script>

<template>
  <h3>Mortgage Calculator</h3>

  <div class="mortgageCalcContainer">
    <div class="containerRow">
      <label for="homeValue">Home Value</label>
    </div>
    <div class="containerRow">
      <input name="homeValue" type="text" />
    </div>
    <div class="containerRow">
      <label for="downPayment">Down Payment</label>
    </div>
    <div class="containerRow">
      <input name="downPayment" type="text" />
    </div>
    <div class="containerRow">
      <label for="loanAmount">Loan Payment</label>
    </div>
    <div class="containerRow">
      <input name="loanAmount" type="text" />
    </div>
    <div class="containerRow">
      <label for="interestRate">Interest Rate</label>
    </div>
    <div class="containerRow">
      <input name="interestRate" type="text" />
    </div>
    <div class="containerRow">
      <label for="loanTerm">Loan Term (years)</label>
    </div>
    <div class="containerRow">
      <input name="loanTerm" type="text" />
    </div>
    <div class="containerRow">
      <label for="startDate">Start Date</label>
    </div>
    <div class="containerRow">
      <input name="startDate" type="text" />
    </div>
    <div class="containerRow">
      <label for="propertyTax">Property Tax</label>
    </div>
    <div class="containerRow">
      <input name="propertyTax" type="text" />
    </div>
    <div class="containerRow">
      <label for="pmi">PMI</label>
    </div>
    <div class="containerRow">
      <input name="pmi" type="text" />
    </div>
    <div class="containerRow">
      <label for="homeInsurance">Home Insurance</label>
    </div>
    <div class="containerRow">
      <input name="homeInsurance" type="text" />
    </div>
    <div class="containerRow">
      <label for="monthlyHOA">Monthly HOA</label>
    </div>
    <div class="containerRow">
      <input name="monthlyHOA" type="text" />
    </div>
  </div>
</template>

<style scoped>
label {
  padding-right: 0.75rem;
  text-align: left;
}

h3 {
  margin-left: 10%;
}
.mortgageCalcContainer {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-column-gap: 2rem;
  padding-left: 20px;
  place-self: center;
  column-gap: 30px;
  width: 40%;
}

.containerRow {
  margin-bottom: 0.75rem;
}
</style>
