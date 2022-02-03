<template>
  <div class="contentBody">
    <div class="text1">Stake LOOKS, earn up to</div>
    <div class="text2">782.27% ARP</div>

    <form action="">
      <div class="formBody">
        <div class="formHeader">
          <div>Limit Order Swap</div>
          <div class="formHeader-icon">
            <img src="~/assets/refreshIcon.png" alt="" />
          </div>
        </div>

        <div class="formBox big">
          <div class="label label-left">
            <div class="labelText">You Pay</div>
            <div class="label-base">
              <button id="dropdownButton" data-dropdown-toggle="dropdown" type="button">
                <img src="~/assets/ethereum.png" alt="" />
                <div>ETH</div>
                <svg class="ml-2 w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" ></path>
                </svg>
              </button>
            </div>
          </div>

          <div class="label label-right">
            <div class="labelText">Max</div>
            <div class="labelText-base">0.0</div>
          </div>
        </div>

        <div class="formBox small">
          <div class="label-s">ETH Price</div>
          <div class="label-s">0</div>
        </div>

        <div class="formBox big relative">
          <img src="~/assets/button.png" alt="" class="extra-button">
          <div class="label label-left">
            <div class="labelText">You receive</div>
            <div class="label-base">
              <button id="dropdownButton" data-dropdown-toggle="dropdown" type="button">
                <img src="~/assets/ethereum.png" alt="" />
                <div>USDC</div>
                <svg class="ml-2 w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" >
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" ></path>
                </svg>
              </button>
            </div>
          </div>

          <div class="label label-right">
            <div class="labelText">1 USDC = 0.00038 ETH</div>
            <div class="labelText-base">0.0</div>
          </div>
        </div>
      </div>

      <input type="submit" value="Transfer" class="formSubmit" />
    </form>
  </div>
</template>

<script>
export default {
  name: "ContentBody",
};
</script>

<style>
.contentBody {
  display: flex;
  flex-direction: column;
  align-items: flex-start;

  background: #f5f3ff;
  border-radius: 16px;
  width: 468px;
  height: 527px;
  margin-top: 10px;
  margin-bottom: 50px;
  padding: 25px;
}

.text1 {
  font-weight: 600;
  font-size: 14px;
  line-height: 20px;
  letter-spacing: 0.01em;
  text-transform: uppercase;
  color: #9ca3af;
  margin: 5px 0px;
}

.text2 {
  font-weight: bold;
  font-size: 35px;
  line-height: 30px;
  letter-spacing: 0.01em;
  color: #1f2937;
  margin-bottom: 20px;
}

.formBody {
  /*display: flex;
  flex-direction: column;
  align-items: flex-start;*/
  padding: 12px 20px 20px;
  width: 418px;
  height: 327px;
  background: #ffffff;
  border-radius: 14px;
}

.formHeader {
  display: flex;
  justify-content: space-between;
  align-items: center;

  width: 100%;
  font-weight: 600;
  font-size: 16px;
  line-height: 30px;
  margin-bottom: 6px;
}

.formHeader-icon {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;

  width: 50px;
  height: 30px;
  background: #f7f7f9;
  border-radius: 8px;
}

.formBox {
  background: #f7f7f9;
  border-radius: 10px;
  width: 378px;
  padding: 15px 20px 15px 15px;
  margin-bottom: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.big {
  height: 90px;
}

.small {
  height: 50px;
  font-weight: 600;
  font-size: 16px;
  line-height: 30px;
}

.relative {
    position: relative;
}

.extra-button {
    position: absolute;
    bottom: 70%;
    left: 45%;
    cursor: pointer;
}

.label {
  display: flex;
  flex-direction: column;
}


.labelText {
  font-weight: 600;
  font-size: 12px;
  line-height: 10px;
  color: #9ca3af;
  margin-bottom: 5px;
}

.label-base {
  padding: 10px;
  width: 110px;
  height: 40px;
  background: #ffffff;
  border-radius: 10px;
}

#dropdownButton {
  display: flex;
  flex-direction: row;
  align-items: center;
}

#dropdownButton img {
    margin-right: 6px;
}

#dropdownButton svg {
    background: #F7F7F9;
border-radius: 4px;
}

.labelText-base {
  font-weight: 600;
  font-size: 26px;
  line-height: 40px;
  color: #d1d5db;
}

.label-s {
  font-weight: 600;
  font-size: 16px;
  line-height: 30px;
  color: #9ca3af;
}

.formSubmit {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;

  padding: 10px 15px;
  width: 418px;
  height: 40px;
  background: #a78bfa;
  border-radius: 12px;
  margin: 20px 0px;

  color: white;
  font-weight: 600;
  font-size: 14px;
  cursor: pointer;
}
</style>