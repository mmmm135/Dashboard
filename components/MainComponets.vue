<script setup lang="ts">

import RightComponents from "./RightComponents.vue";
</script>

<template>

  <div class="MainContent">

    <div class="main">

      <div class="main-head">

        <div class="main-title">
          <span class="exp"> Expenses </span>
          <span class="date"> 01 - 25 March, 2020 </span>
        </div>

        <div class="main-users">
          <img src="../assets/images/user1.png" alt="UserPhoto" class="user1">
          <img src="../assets/images/user2.png" alt="UserPhoto" class="user2">
          <img src="../assets/images/user3.png" alt="UserPhoto" class="user3">
          <a href="*" class="us-button">
          <img src="../assets/images/user+.png" alt="Button" class="user-button">
          </a>
        </div>

      </div>

      <div class="stats">
        <img src="../assets/images/Stats.png" alt="stats">
      </div>

      <div class="expenses">

        <div class="expenses-tittle">
          <span class="exp-tittle">Today</span>
          <div class="exp-info">
            <div class="oval"></div>
            <div class="oval"></div>
            <div class="oval"></div>
          </div>
        </div>


        <div class="expenses-items">

          <div class="expenses-item">
            <div class="exp-item-info">

              <div class="item-icon">
                <img src="../assets/images/cart.png" alt="icon" class="cart">
              </div>

              <div class="item-text">
                <div class="item-tittle"><span class="exp-tittle">Grocery</span></div>
                <div class="item-time"><span class="exp-date">5:12 pm • Belanja di</span></div>
              </div>
            </div>

            <div class="minus">
              <span>-326.800</span>
            </div>
          </div>

          <div class="expenses-item">
            <div class="exp-item-info">

              <div class="item-icon2">
                <img src="../assets/images/bus.png" alt="icon" class="bus">
              </div>

              <div class="item-text">
                <div class="item-tittle"><span class="exp-tittle">Transportation</span></div>
                <div class="item-time"><span class="exp-date">5:12 pm • Naik bus u</span></div>
              </div>
            </div>

            <div class="minus">
              <span>-15.000</span>
            </div>
          </div>

          <div class="expenses-item">
            <div class="exp-item-info">

              <div class="item-icon3">
                <img src="../assets/images/house.png" alt="icon" class="house">
              </div>

              <div class="item-text">
                <div class="item-tittle"><span class="exp-tittle">Housing</span></div>
                <div class="item-time"><span class="exp-date">5:12 pm • Bayar List</span></div>
              </div>
            </div>

            <div class="minus">
              <span>-185.750</span>
            </div>
          </div>

        </div>

        <div class="expenses-tittle">
          <span class="exp-tittle">Monday, 23 March 2020</span>
          <div class="exp-info">
            <div class="oval"></div>
            <div class="oval"></div>
            <div class="oval"></div>
          </div>
        </div>

        <div class="expenses-items">

          <div class="expenses-item">
            <div class="exp-item-info">

              <div class="item-icon4">
                <img src="../assets/images/food.png" alt="icon" class="food">
              </div>

              <div class="item-text">
                <div class="item-tittle"><span class="exp-tittle">Food and Drink</span></div>
                <div class="item-time"><span class="exp-date">5:12 pm • Makan Stea</span></div>
              </div>
            </div>

            <div class="minus">
              <span>-156.000</span>
            </div>
          </div>

          <div class="expenses-item">
            <div class="exp-item-info">

              <div class="item-icon5">
                <img src="../assets/images/butt.png" alt="icon" class="house">
              </div>

              <div class="item-text">
                <div class="item-tittle"><span class="exp-tittle">Entertainment</span></div>
                <div class="item-time"><span class="exp-date">5:12 pm • Nonton Bio</span></div>
              </div>
            </div>

            <div class="minus">
              <span>-35.200</span>
            </div>
          </div>

        </div>




      </div>



    </div>

    <div class="Right-content">
      <RightComponents />
    </div>

  </div>

</template>


<style scoped lang="scss">

.MainContent {
  display: flex;
  width: 1060px;
  height: 860px;
  margin-left: 83px;
  margin-top: 20px;
  border-radius: 30px;
  background-color: white;
}

.main {
  width: 510px;
  height: 741px;
  margin: 60px 100px 59px 100px ;
}

.main-head {
  display: flex;
}

.main-title {
  padding-bottom: 46px;
}

.main-title span {
  display: block;
}

.exp {
  font-size: 40px;
  font-weight: 600;
  text-align: left;
}

.date {
  font-size: 16px;
  font-weight: 400;
  text-align: left;
  opacity: 0.5;
}

.main-users {
  background-color: #cecece;
}

.user1 {
  position: absolute;
  top: 93px;
  left: 847px;
}

.user2 {
  position: absolute;
  top: 93px;
  left: 875px;
}

.user3 {
  position: absolute;
  top: 93px;
  left: 903px;
}

.user-button {
    position: absolute;
    top: 97px;
    left: 946px;
  &:hover {
    transition: all ease-in-out .2s;
    cursor: pointer;
    filter: brightness(95%);
  }
}

.expenses-tittle {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-bottom: 7.5px;
  margin-bottom: 25.5px;
  padding-top: 47px;
  border-bottom: 0.5px solid #DEDEDE;
}

.exp-info {
  display: flex;
  justify-content: center;
  align-items: center;
  &:hover {
    transition: all ease-in-out .2s;
    cursor: pointer;
    filter: brightness(75%);
  }
}

.exp-tittle {
  font-size: 18px;
  font-weight: 500;
  text-align: left;
}

.item-icon {

}

.oval {
  width: 5px;
  height: 5px;
  border-radius: 3px;
  margin-right: 5px;
  background-color: #D8D8D8;
}

.item-text {
  padding-left: 17px;
}

.expenses-item {
  display: flex;
  justify-content: space-between;
  margin-bottom: 24px;
}

.expenses-item:last-child {
  margin-bottom: 33.5px;
}

.exp-item-info {
  display: flex;
}

.minus {
  font-size: 16px;
  font-weight: 600;
  text-align: right;
}

.exp-tittle {
  font-size: 16px;
  font-weight: 500;
  text-align: left;
}

.exp-date {
  font-size: 14px;
  font-weight: 400;
  text-align: left;
  opacity: 50%;
}

.item-icon {
  justify-content: center;
  align-items: center;
  display: flex;
  width: 48px;
  height: 48px;
  border-radius: 24px;
  background-color: #32A7E2;
}

.item-icon2 {
  justify-content: center;
  align-items: center;
  display: flex;
  width: 48px;
  height: 48px;
  border-radius: 24px;
  background-color: #B548C6;
}

.item-icon3 {
  justify-content: center;
  align-items: center;
  display: flex;
  width: 48px;
  height: 48px;
  border-radius: 24px;
  background-color: #FF8700;
}

.item-icon4 {
  justify-content: center;
  align-items: center;
  display: flex;
  width: 48px;
  height: 48px;
  border-radius: 24px;
  background-color: #DC3434;
}

.item-icon5 {
  justify-content: center;
  align-items: center;
  display: flex;
  width: 48px;
  height: 48px;
  border-radius: 24px;
  background-color: #4BA83D;
}

.Right-content {
  width: 350px;
  height: 860px;
  background-color: #F9FAFC;
  border-radius: 0 30px 30px 0;
}

</style>