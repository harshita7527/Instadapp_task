<template>
  <div class="mainContent">
    <div class="swapButton">
      <button class="selected">Deposit</button>
      <button>My Orders</button>
    </div>
    <ContentBody />
  </div>
</template>

<script>
import ContentBody from "../components/DepositContentBody.vue";

export default {
  name: "MainContent",
  components: {
      ContentBody
  }
};
</script>

<style scoped>
.mainContent {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.swapButton {
  display: flex;
  justify-content: space-around;
  align-items: center;
  background: #f5f3ff;
  border-radius: 16px;
  width: 468px;
  height: 56px;
  margin: 10px 0px;
}

button {
  border-radius: 12px;
  width: 222px;
  height: 40px;
}

.selected {
    background: #FFFFFF;
}


</style>