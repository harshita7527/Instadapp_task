<template>
  <header class="header">
    <div class="logo">
      <div class="logoIcon">
        <img src="~/assets/Vector.png" alt="" />
      </div>
      <div class="logoText">Logoooo</div>
    </div>
  </header>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>


<style scoped>
.header {
  height: 80px;
  width: 100%;
  left: 0px;
  top: 0px;
  background: rgba(255, 255, 255, 0.0001);
  border-radius: 20px 20px 0px 0px;
  margin-bottom: 30px;
}

.logo {
  display: flex;
  padding-left: 60px;
  padding-top: 20px;
  align-items: center;
}

.logoIcon {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;

  background: #a78bfa;
  border-radius: 30px;
  width: 40px;
  height: 40px;
  left: 0px;
  top: 0px;
  margin: 0px 15px;
}

.logoText {
  font-weight: bold;
  font-size: 22px;
  line-height: 30px;
  letter-spacing: 0.01em;
}
</style>