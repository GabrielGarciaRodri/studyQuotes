<template>
  <div class="rectangle-parent8">
    <div class="frame-child22" />
    <div class="frame-wrapper4">
      <div class="rectangle-parent9">
        <img class="rectangle-icon" alt="" src="/rectangle-387@2x.png" />
        <div class="puss-in-boots-the-last-wish-parent">
          <h3 class="puss-in-boots1">Puss In Boots The Last Wish</h3>
          <div class="show-this-ticket1">Show this ticket at the entrance</div>
        </div>
      </div>
    </div>
    <div class="line-wrapper">
      <div class="line-div" />
    </div>
    <div class="frame-wrapper5">
      <div class="frame-parent7">
        <div class="frame-parent8">
          <div class="frame-wrapper6">
            <div class="cinema-group">
              <b class="cinema3">Cinema</b>
              <a class="hartono-mall-121">Hartono Mall 12</a>
            </div>
          </div>
          <div class="frame-parent9">
            <div class="date-parent">
              <b class="date1">Date</b>
              <b class="sun-feb1">Sun , Feb 12th 2023</b>
            </div>
            <div class="date-parent">
              <b class="cinema-hall1">Cinema Hall #</b>
              <a class="cinema-a1">Cinema A</a>
            </div>
            <div class="date-parent">
              <b class="cost1">Cost</b>
              <b class="b3">$26,99</b>
            </div>
          </div>
        </div>
        <div class="rectangle-parent10">
          <img class="frame-child23" alt="" src="/rectangle-376@2x.png" />
          <div class="frame-wrapper7">
            <div class="order-info-label-parent">
              <div class="date-parent">
                <b class="time1">Time</b>
                <a class="order-info-value">13:00 </a>
              </div>
              <div class="date-parent">
                <b class="cost1">Seat</b>
                <b class="c51">C5</b>
              </div>
              <div class="order-info-label2">
                <b class="order-id1">Order ID</b>
                <div class="div7">12345678</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="line-group">
      <div class="frame-child24" />
      <div class="barcode-wrapper">
        <img class="barcode-icon1" loading="lazy" alt="" src="/barcode.svg" />
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "GroupComponent",
  });
</script>
<style scoped>
  .frame-child22 {
    align-self: stretch;
    height: 620px;
    position: relative;
    border-radius: var(--br-xl);
    background-color: var(--color-white);
    display: none;
  }
  .rectangle-icon {
    align-self: stretch;
    flex: 1;
    position: relative;
    border-radius: var(--br-3xs);
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
    object-fit: cover;
    z-index: 1;
  }
  .puss-in-boots1 {
    margin: 0;
    align-self: stretch;
    flex: 1;
    position: relative;
    font-size: inherit;
    font-weight: 700;
    font-family: inherit;
    z-index: 1;
  }
  .show-this-ticket1 {
    width: 205px;
    height: 20px;
    position: relative;
    font-size: var(--font-size-smi);
    color: var(--color-gray-100);
    display: inline-block;
    z-index: 1;
  }
  .puss-in-boots-the-last-wish-parent {
    align-self: stretch;
    height: 50px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .rectangle-parent9 {
    align-self: stretch;
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    justify-content: flex-start;
    gap: var(--gap-7xs);
  }
  .frame-wrapper4 {
    align-self: stretch;
    height: 182px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-end;
    padding: 0px var(--padding-lgi) var(--padding-smi) var(--padding-4xl);
    box-sizing: border-box;
  }
  .line-div {
    height: 1px;
    flex: 1;
    position: relative;
    border-top: 1px solid var(--color-gainsboro);
    box-sizing: border-box;
    z-index: 1;
  }
  .line-wrapper {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-end;
    padding: 0px var(--padding-5xl) 0px var(--padding-3xl);
  }
  .cinema3 {
    width: 54px;
    position: absolute;
    margin: 0 !important;
    top: -17px;
    left: 0px;
    display: inline-block;
    z-index: 1;
  }
  .hartono-mall-121 {
    text-decoration: none;
    align-self: stretch;
    flex: 1;
    position: relative;
    font-size: var(--font-size-xl);
    text-transform: uppercase;
    font-weight: 700;
    color: var(--color-black);
    z-index: 2;
  }
  .cinema-group {
    align-self: stretch;
    flex: 1;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    position: relative;
  }
  .frame-wrapper6 {
    align-self: stretch;
    height: 30px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 0px 0px var(--padding-12xs);
    box-sizing: border-box;
  }
  .date1 {
    position: relative;
    display: inline-block;
    min-width: 32px;
    z-index: 1;
  }
  .sun-feb1 {
    position: relative;
    font-size: var(--font-size-mini);
    color: var(--color-black);
    z-index: 1;
  }
  .date-parent {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-6xs);
  }
  .cinema-hall1 {
    position: relative;
    display: inline-block;
    min-width: 97px;
    z-index: 1;
  }
  .cinema-a1 {
    text-decoration: none;
    position: relative;
    font-size: var(--font-size-mini);
    font-weight: 700;
    color: var(--color-black);
    display: inline-block;
    min-width: 76px;
    z-index: 1;
  }
  .cost1 {
    position: relative;
    display: inline-block;
    min-width: 31px;
    z-index: 1;
  }
  .b3 {
    position: relative;
    font-size: var(--font-size-mini);
    display: inline-block;
    color: var(--color-black);
    min-width: 51px;
    white-space: nowrap;
    z-index: 1;
  }
  .frame-parent9 {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-xl) 0px 0px;
    gap: var(--gap-lgi);
  }
  .frame-parent8 {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-23xl-5);
  }
  .frame-child23 {
    width: 47px;
    height: 48px;
    position: relative;
    border-radius: var(--br-8xs);
    object-fit: cover;
    z-index: 1;
  }
  .time1 {
    position: relative;
    display: inline-block;
    min-width: 34px;
    z-index: 1;
  }
  .order-info-value {
    text-decoration: none;
    position: relative;
    font-size: var(--font-size-mini);
    font-weight: 700;
    color: var(--color-black);
    display: inline-block;
    min-width: 39px;
    white-space: nowrap;
    z-index: 1;
  }
  .c51 {
    position: relative;
    font-size: var(--font-size-mini);
    display: inline-block;
    color: var(--color-black);
    min-width: 22px;
    z-index: 1;
  }
  .order-id1 {
    position: relative;
    display: inline-block;
    min-width: 55px;
    z-index: 1;
  }
  .div7 {
    position: relative;
    font-size: var(--font-size-mini);
    letter-spacing: 0.06em;
    text-transform: uppercase;
    font-weight: 600;
    color: var(--color-black);
    display: inline-block;
    min-width: 78px;
    z-index: 1;
  }
  .order-info-label2 {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-6xs);
  }
  .order-info-label-parent {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-lgi);
  }
  .frame-wrapper7 {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-end;
    padding: 0px var(--padding-5xs) 0px 0px;
  }
  .rectangle-parent10 {
    width: 86px;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    justify-content: flex-start;
    gap: var(--gap-23xl);
  }
  .frame-parent7 {
    flex: 1;
    display: flex;
    flex-direction: row;
    align-items: flex-end;
    justify-content: flex-start;
    gap: var(--gap-mini);
  }
  .frame-wrapper5 {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-end;
    padding: 0px var(--padding-lgi) var(--padding-5xs) var(--padding-4xl);
    font-size: var(--font-size-smi);
    color: var(--color-gray-100);
  }
  .frame-child24 {
    align-self: stretch;
    height: 0.5px;
    position: relative;
    border-top: 0.5px dashed var(--color-black);
    box-sizing: border-box;
    z-index: 1;
  }
  .barcode-icon1 {
    height: 49px;
    width: 267px;
    position: relative;
    z-index: 1;
  }
  .barcode-wrapper {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-10xl);
  }
  .line-group {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-base-5);
  }
  .rectangle-parent8 {
    position: absolute;
    top: -285px;
    left: 437px;
    border-radius: var(--br-xl);
    background-color: var(--color-white);
    width: 325px;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    justify-content: flex-start;
    padding: var(--padding-7xl) 0px var(--padding-xl);
    box-sizing: border-box;
    gap: var(--gap-smi);
    z-index: 1;
    text-align: left;
    font-size: var(--font-size-xl);
    color: var(--color-black);
    font-family: var(--font-poppins);
  }
</style>
