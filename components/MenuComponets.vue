<script setup lang="ts">

</script>

<template>
  <div class="menu">
    <div class="profile">
      <div class="avatar">
        <div class="avatar-notifications">
          <span class="notifications-number">
            4
          </span>
        </div>
        <img
          class="avatar-img"
          src="../assets/images/Profile.png"
          alt="profile__image"
        >
      </div>

      <div class="profile-title">
        <span>Samantha</span>
      </div>

      <div class="profile-email">
        <span>samantha@email.com</span>
      </div>
    </div>



    <div class="menu-text">
      <a href="*" class="menu-items"> Dashboard <br> </a>
      <a href="*" class="menu-item"> Expenses <br> </a>
      <a href="*" class="menu-items"> Wallets <br> </a>
      <a href="*" class="menu-items"> Summary <br> </a>
      <a href="*" class="menu-items"> Accounts <br> </a>
      <a href="*" class="menu-items"> Settings <br> </a>

    </div>

  </div>
</template>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700;800;900&display=swap');

.menu {
  padding-top: 80px;
}

.avatar-notifications {
  width: 29px;
  height: 29px;
  border-radius: 15px;
  text-align: center;
  align-items: center;
  justify-content: center;
  display: flex;
  position: absolute;
  top: 65px;
  left: 137px;
  background-color: #DC3434;
}

.notifications-number {
  font-size: 13px;
  font-weight: 600;
  color: #fff;
}

.profile-title {
  padding-top: 20px;
  padding-bottom: 5px;
  font-weight: 600;
  font-size: 30px;
  color: #fff;
}

.profile-email {
  font-weight: 400;
  font-size: 17px;
  color: #fff;
  opacity: 60%;
}

.menu-item {
  font-size: 25px;
  font-weight: 600;
  text-align: left;
  line-height: 60px;
  color: #fff;
  opacity: 1;
  text-decoration: none;
  &:hover {
    transition: all ease-in-out .2s;
    cursor: pointer;
    opacity: 85%;
  }
}

.menu-items {
  font-size: 25px;
  font-weight: 600;
  text-align: left;
  line-height: 60px;
  color: #fff;
  opacity: 50%;
  text-decoration: none;
  &:hover {
    transition: all ease-in-out .2s;
    cursor: pointer;
    opacity: 80%;
  }
}

.menu-text {
  padding-top: 117px;
  padding-bottom: 184px;
}
</style>