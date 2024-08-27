<template>
  <div class="ticket-layout-parent">
    <div class="ticket-layout">
      <div class="seat-types">
        <div class="seat-icon-row-parent">
          <div class="seat-icon-row" />
          <div class="seat-type-label">
            <div class="seat-type-placeholder">13:00</div>
          </div>
          <div class="d1">$ 5.25 •3D</div>
        </div>
        <div class="rectangle-parent13">
          <div class="frame-child27" />
          <div class="wrapper">
            <div class="div8">15:45</div>
          </div>
          <div class="d2">$ 5.99 •3D</div>
        </div>
        <div class="rectangle-parent14">
          <div class="frame-child27" />
          <div class="container">
            <div class="div9">18:50</div>
          </div>
          <div class="d3">$ 4.50 •3D</div>
        </div>
        <div class="seat-type-detail">
          <div class="icon1" />
          <div class="seat-type-name">20:30</div>
          <div class="seat-type-tag">
            <div class="d4">$ 6.5 •3D</div>
          </div>
        </div>
      </div>
      <div class="price-details-parent">
        <div class="price-details">
          <h3 class="price">Price</h3>
          <div class="price-value">$24,99</div>
        </div>
        <button class="buy1">
          <div class="buy-item" />
          <div class="buy-ticket1">Buy ticket</div>
        </button>
      </div>
    </div>
    <div class="home-indicator8">
      <div class="home-indicator9" />
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "FrameComponent2",
  });
</script>
<style scoped>
  .seat-icon-row {
    width: calc(100% - 22px);
    height: calc(100% + 22px);
    position: absolute;
    margin: 0 !important;
    top: 0px;
    right: -62px;
    bottom: -22px;
    left: 84px;
    border-radius: var(--br-7xs);
    background-color: var(--color-red-100);
    border: 2px solid var(--color-red-100);
    box-sizing: border-box;
    transform: rotate(90deg);
    transform-origin: 0 0;
  }
  .seat-type-placeholder {
    width: 49px;
    position: relative;
    display: inline-block;
    min-width: 49px;
    white-space: nowrap;
    z-index: 1;
  }
  .seat-type-label {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-7xs) 0px var(--padding-9xs);
  }
  .d1 {
    align-self: stretch;
    position: relative;
    font-size: var(--font-size-smi);
    font-weight: 600;
    font-family: var(--font-gilroy);
    display: inline-block;
    min-width: 59px;
    z-index: 1;
  }
  .seat-icon-row-parent {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-5xs) var(--padding-xs) var(--padding-3xs)
      var(--padding-smi);
    box-sizing: border-box;
    position: relative;
    gap: var(--gap-9xs);
    min-width: 55px;
    color: var(--color-white);
  }
  .frame-child27 {
    width: calc(100% - 22px);
    height: calc(100% + 22px);
    position: absolute;
    margin: 0 !important;
    top: 0px;
    right: -62px;
    bottom: -22px;
    left: 84px;
    border-radius: var(--br-xs);
    background-color: var(--color-whitesmoke);
    transform: rotate(90deg);
    transform-origin: 0 0;
  }
  .div8 {
    width: 47px;
    position: relative;
    display: inline-block;
    min-width: 47px;
    white-space: nowrap;
    z-index: 1;
  }
  .wrapper {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-7xs) 0px var(--padding-8xs);
  }
  .d2 {
    align-self: stretch;
    position: relative;
    font-size: var(--font-size-smi);
    font-weight: 500;
    font-family: var(--font-gilroy);
    color: var(--color-darkgray-200);
    display: inline-block;
    min-width: 58px;
    z-index: 1;
  }
  .rectangle-parent13 {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-5xs) var(--padding-smi) var(--padding-2xs);
    box-sizing: border-box;
    position: relative;
    gap: var(--gap-9xs);
    min-width: 55px;
  }
  .div9 {
    width: 48px;
    position: relative;
    display: inline-block;
    min-width: 48px;
    white-space: nowrap;
    z-index: 1;
  }
  .container {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-6xs) 0px var(--padding-8xs);
  }
  .d3 {
    align-self: stretch;
    position: relative;
    font-size: var(--font-size-smi);
    font-weight: 500;
    font-family: var(--font-gilroy);
    color: var(--color-darkgray-200);
    display: inline-block;
    min-width: 60px;
    z-index: 1;
  }
  .rectangle-parent14 {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-5xs) var(--padding-xs) var(--padding-2xs);
    box-sizing: border-box;
    position: relative;
    gap: var(--gap-9xs);
    min-width: 55px;
  }
  .icon1 {
    width: 62px;
    height: calc(100% + 22px);
    position: absolute;
    margin: 0 !important;
    top: 0px;
    right: -89px;
    bottom: -22px;
    border-radius: var(--br-xs);
    background-color: var(--color-whitesmoke);
    transform: rotate(90deg);
    transform-origin: 0 0;
  }
  .seat-type-name {
    width: 52px;
    position: relative;
    display: inline-block;
    white-space: nowrap;
    z-index: 1;
  }
  .d4 {
    width: 52px;
    position: relative;
    font-weight: 500;
    display: inline-block;
    flex-shrink: 0;
    z-index: 1;
  }
  .seat-type-tag {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 0px 0px var(--padding-12xs);
    font-size: var(--font-size-smi);
    color: var(--color-darkgray-200);
    font-family: var(--font-gilroy);
  }
  .seat-type-detail {
    width: 57px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-5xs) 0px var(--padding-2xs) var(--padding-mini);
    box-sizing: border-box;
    position: relative;
    gap: var(--gap-9xs);
  }
  .seat-types {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-lg);
  }
  .price {
    margin: 0;
    position: relative;
    font-size: inherit;
    font-weight: 500;
    font-family: inherit;
    display: inline-block;
    min-width: 45px;
  }
  .price-value {
    position: relative;
    font-size: var(--font-size-xl);
    font-weight: 600;
    display: inline-block;
    min-width: 70px;
    white-space: nowrap;
  }
  .price-details {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-5xs);
  }
  .buy-item {
    height: 53px;
    width: 221px;
    position: relative;
    border-radius: var(--br-3xs);
    background-color: var(--color-red-100);
    display: none;
  }
  .buy-ticket1 {
    width: 78px;
    position: relative;
    font-size: var(--font-size-base);
    font-weight: 600;
    font-family: var(--body-medium-regular);
    color: var(--color-white);
    text-align: center;
    display: inline-block;
    min-width: 78px;
    z-index: 1;
  }
  .buy1 {
    cursor: pointer;
    border: none;
    padding: var(--padding-mid) var(--padding-52xl);
    background-color: var(--color-red-100);
    border-radius: var(--br-3xs);
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    white-space: nowrap;
  }
  .price-details-parent {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-23xl);
    max-width: 100%;
    font-size: var(--font-size-lg);
    color: var(--color-white);
    font-family: var(--body-medium-regular);
  }
  .ticket-layout {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 0px 0px var(--padding-11xl);
    box-sizing: border-box;
    gap: var(--gap-29xl);
    max-width: 100%;
  }
  .home-indicator9 {
    height: 5px;
    width: 134px;
    position: relative;
    border-radius: var(--br-81xl);
    background-color: var(--color-white);
  }
  .home-indicator8 {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: center;
    padding: var(--padding-mid) var(--padding-xl) var(--padding-5xs)
      var(--padding-2xl);
  }
  .ticket-layout-parent {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    justify-content: flex-start;
    gap: var(--gap-19xl);
    max-width: 100%;
    text-align: center;
    font-size: var(--font-size-xl);
    color: var(--color-darkslategray-200);
    font-family: var(--font-gilroy-bold);
  }
</style>
