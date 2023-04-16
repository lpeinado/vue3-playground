<template>
  <center class="GridContainer">
    <div class="grid-cell">1</div>
    <div class="grid-cell">2</div>
    <div class="grid-cell">3</div>
    <div class="grid-cell">4</div>
    <div class="grid-cell">5</div>
    <div class="grid-cell">6</div>
    <div class="grid-cell">7</div>
    <div class="grid-cell">8</div>
    <div class="grid-cell">9</div>
    <div class="grid-cell">99</div>
    <div class="grid-cell">10</div>
  </center>
</template>

<script setup lang="ts">

</script>

<style scoped lang="scss">
.GridContainer{
  display: grid;
  width: fit-content;
  margin: auto;
  grid-template-columns: 200px 200px 200px;
  grid-template-rows: 200px 100px;
  grid-auto-rows: 200px;
  grid-gap: 30px;
  .grid-cell{
    border: 1px solid aliceblue;
    background-color:antiquewhite;
    width: 100px;
    padding: 20px;
  }
  .grid-cell:nth-child(even){
    background-color:lightblue;
  }
}

</style>