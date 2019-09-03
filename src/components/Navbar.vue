<template>
  <div class="navbar">
    <div class="navbar-container navbar-logo-container">
      <img class="navbar-logo" src="../assets/logo.png" alt="Applover's logo" />
    </div>
    <nav class="navbar-container navbar-options">
      <label for="language">Select language:</label>
      <button class="navbar-button">My organization</button>
    </nav>
  </div>
</template>

<style lang="scss" scoped>
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  top: 0px;
  left: 0px;
  width: 100%;
  height: 80px;
  background: #ffffff 0% 0% no-repeat padding-box;
  box-shadow: 0px 3px 12px #c9c9c929;
  & .navbar-container {
    width: 50%;
    & .navbar-logo {
      margin-left: 10%;
    }
  }
  & .navbar-options {
    display: flex;
    justify-content: center;
    & .navbar-button {
      width: 118px;
      height: 32px;
      background: #77779d 0% 0% no-repeat padding-box;
      border-radius: 3px;
      border: none;
      text-align: center;
      letter-spacing: 0;
      color: #ffffff;
      transition: all 0.4s ease 0s;
      cursor: pointer;
      &:hover {
        background: darken(#77779d, 15%);
      }
    }
  }
}
</style>