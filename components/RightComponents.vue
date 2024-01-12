<script setup lang="ts">

</script>

<template>

  <div class="stats">

    <div class="stats-tittle">
      Where your money go?
    </div>

    <div class="stats-items">

      <div class="stats-item">
        <div class="stats-text">
          <div class="stats-tit">Food and Drinks</div>
          <div class="stats-number">872.400</div>
        </div>
        <div class="stats-rectangle">
          <div class="rectangle-1"></div>
        </div>
      </div>

      <div class="stats-item">
        <div class="stats-text">
          <div class="stats-tit">Shopping</div>
          <div class="stats-number">1.378.200</div>
        </div>
        <div class="stats-rectangle">
          <div class="rectangle-2"></div>
        </div>
      </div>

      <div class="stats-item">
        <div class="stats-text">
          <div class="stats-tit">Housing</div>
          <div class="stats-number">928.500</div>
        </div>
        <div class="stats-rectangle">
          <div class="rectangle-3"></div>
        </div>
      </div>

      <div class="stats-item">
        <div class="stats-text">
          <div class="stats-tit">Transportation</div>
          <div class="stats-number">420.700</div>
        </div>
        <div class="stats-rectangle">
          <div class="rectangle-4"></div>
        </div>
      </div>

      <div class="stats-item">
        <div class="stats-text">
          <div class="stats-tit">Vehicle</div>
          <div class="stats-number">520.000</div>
        </div>
        <div class="stats-rectangle">
          <div class="rectangle-5"></div>
        </div>
      </div>

    </div>

  </div>

  <div class="tips">

      <img src="../assets/images/Illustration.png" alt="" class="tips-img1">
      <img src="../assets/images/Illustration%20(1).png" alt="" class="tips-img2">

    <div class="tips-block">
      <div class="block-text">
        <div class="block-tittle">Save more money</div>
        <div class="block-description">eiusmod tempor incididunt ut <br> labore et dolore magna aliqua. <br> Ut enim ad minim.</div>
      </div>
      <a href="*" class="tips-button">
        <div class="tips-button">
           <span>VIEW TIPS</span>
        </div>
      </a>
    </div>

  </div>

</template>

<style scoped lang="scss">

.stats {
  margin: 76px 50px 0 50px;
  width: 250px;
  height: 365px;
}

.stats-tittle {
  font-size: 20px;
  text-align: left;
}

.stats-item {
  display: block;
  width: 250px;
  height: 37px;
  margin-top: 30px;
}

.stats-text {
  display: flex;
  justify-content: space-between;
  width: 100%;
  height: 32px;
}

.stats-tit {
  font-size: 13px;
  font-weight: 500;
  text-align: left;
}

.stats-number {
  font-size: 13px;
  font-weight: 400;
  text-align: left;
}

.stats-rectangle {
  display: flex;
  width: 250px;
  height: 5px;
  border-radius: 3px;
  background-color: #ECEFF5;
}

.rectangle-1 {
  display: flex;
  width: 70px;
  height: 5px;
  border-radius: 3px;
  background-color: #31BA96;
}

.rectangle-2 {
  display: flex;
  width: 110px;
  height: 5px;
  border-radius: 3px;
  background-color: #31BA96;
}

.rectangle-3 {
  display: flex;
  width: 90px;
  height: 5px;
  border-radius: 3px;
  background-color: #31BA96;
}

.rectangle-4 {
  display: flex;
  width: 60px;
  height: 5px;
  border-radius: 3px;
  background-color: #31BA96;
}

.rectangle-5 {
  display: flex;
  width: 90px;
  height: 5px;
  border-radius: 3px;
  background-color: #31BA96;
}

.tips {

}

.tips-img1 {
  position: absolute;
  top: 547px;
  left: 1145px;

}

.tips-img2 {
  position: absolute;
  top: 528px;
  left: 1292px;
}

.tips-block {
  margin: 101px 50px 0 50px;
  padding-left: 25px;
  width: 250px;
  height: 258px;
  border-radius: 15px;
  background-color: #EDF0F6;
}

.block-tittle {
  margin-bottom: 4px;
  padding-top: 77px;
  font-size: 16px;
  font-weight: 600;
  text-align: left;
}

.block-description {
  margin-bottom: 20px;
  font-size: 12px;
  font-weight: 400;
  text-align: left;
  color: #404852;
  opacity: 70%;
}

.tips-button {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 200px;
  height: 45px;
  border-radius: 10px;
  text-decoration: none;
  color: #fff;
  background-color: #101010;
  &:hover {
    transition: all ease-in-out .2s;
    cursor: pointer;
    opacity: 80%;
  }
}

.tips-button span {
  font-size: 13px;
  font-weight: 600;
  text-align: left;
}

</style>