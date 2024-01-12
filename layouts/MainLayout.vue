<script setup lang="ts">

import MenuComponets from "../components/MenuComponets.vue";
import MainComponets from "../components/MainComponets.vue";
</script>

<template>
  <div class="wrapper">
    <MenuComponets />
    <MainComponets />
  </div>
</template>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700;800;900&display=swap');

.wrapper {
  display: flex;
  font-family: Poppins, sans-serif;
  padding-top: 0;
  padding-left: 80px;
  width: 100%;
  height: 1080px;
  background-color: #101010;
}
</style>