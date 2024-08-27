<template>
  <div class="order-content">
    <div class="order-items">
      <div class="order-number-container">
        <span>ORDER NUMBER : </span>
        <span class="span">123456786</span>
      </div>
      <div class="order-items-details">
        <div class="order-items-type">
          <div class="ticket1">1 TICKET</div>
          <div class="c52">c5</div>
        </div>
        <img class="order-items-type1" loading="lazy" alt="" />
        <div class="order-items-type">
          <div class="regular-seat">rEGULAR SEAT</div>
          <div class="x-3">
            <span class="span1">$24,99 </span>
            <span class="x">X</span>
            <span class="span1"> 3</span>
          </div>
        </div>
        <img class="order-items-type1" alt="" />
        <div class="order-items-type">
          <div class="service-fee">SERVICE FEE</div>
          <div class="x-1">
            <span class="span1">$1,99 </span>
            <span class="x">x 1</span>
          </div>
        </div>
        <img class="order-items-type1" alt="" />
      </div>
      <div class="payment-method">
        <div class="payment-method1">Payment method</div>
        <div class="card">
          <div class="card-child" />
          <div class="card-info">
            <img
              class="payment-methodmastercard-icon"
              loading="lazy"
              alt=""
              src="/payment-methodmastercard.svg"
            />
            <div class="card-number">
              <div class="card-number-details">
                <div class="mastercard">MasterCard</div>
                <div class="card-number-value">**** **** 0998 7865</div>
              </div>
            </div>
          </div>
          <div class="card-icon">
            <img
              class="card-icon-child"
              loading="lazy"
              alt=""
              src="/group-48095462.svg"
            />
          </div>
        </div>
        <div class="complete">
          <div class="complete-child" />
          <div class="complete-your-payment">Complete your payment in</div>
          <div class="payment-timer">04:59</div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "OrderContent",
  });
</script>
<style scoped>
  .span {
    color: var(--color-white);
  }
  .order-number-container {
    position: relative;
    text-transform: capitalize;
    font-weight: 600;
  }
  .ticket1 {
    position: relative;
    text-transform: capitalize;
    font-weight: 600;
    display: inline-block;
    min-width: 66px;
  }
  .c52 {
    position: relative;
    text-transform: capitalize;
    font-weight: 600;
    display: inline-block;
    min-width: 21px;
  }
  .order-items-type {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: space-between;
    gap: var(--gap-xl);
  }
  .order-items-type1 {
    align-self: stretch;
    position: relative;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
    object-fit: contain;
    margin-top: -1px;
  }
  .regular-seat {
    position: relative;
    text-transform: capitalize;
    font-weight: 600;
    display: inline-block;
    min-width: 113px;
  }
  .span1 {
    text-transform: capitalize;
  }
  .x {
    text-transform: lowercase;
  }
  .x-3 {
    position: relative;
    font-weight: 600;
    display: inline-block;
    min-width: 80px;
  }
  .service-fee {
    position: relative;
    text-transform: capitalize;
    font-weight: 600;
    display: inline-block;
    min-width: 95px;
  }
  .x-1 {
    position: relative;
    font-weight: 600;
    display: inline-block;
    min-width: 64px;
  }
  .order-items-details {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-base-4);
    font-size: var(--font-size-mini);
  }
  .payment-method1 {
    width: 147px;
    position: relative;
    line-height: 13px;
    font-weight: 500;
    display: inline-block;
  }
  .card-child {
    height: 69.8px;
    width: 333px;
    position: relative;
    border-radius: var(--br-3xs);
    background-color: var(--color-gray-200);
    border: 1px solid var(--color-gray-800);
    box-sizing: border-box;
    display: none;
    max-width: 100%;
  }
  .payment-methodmastercard-icon {
    height: 43.7px;
    width: 66px;
    position: relative;
    border-radius: var(--br-5xs);
    overflow: hidden;
    flex-shrink: 0;
    z-index: 1;
  }
  .mastercard {
    width: 102px;
    position: relative;
    line-height: 13px;
    font-weight: 500;
    display: flex;
    align-items: center;
    justify-content: center;
    z-index: 1;
  }
  .card-number-value {
    align-self: stretch;
    position: relative;
    font-size: var(--font-size-xs);
    line-height: 13px;
    font-weight: 500;
    display: inline-block;
    min-width: 122px;
    z-index: 1;
  }
  .card-number-details {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-2xs);
  }
  .card-number {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-10xs-7) 0px 0px;
  }
  .card-info {
    width: 201.8px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-sm-8);
  }
  .card-icon-child {
    width: 21.7px;
    height: 21.7px;
    position: relative;
    z-index: 1;
  }
  .card-icon {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-end;
    padding: 0px 0px var(--padding-2xs-7);
  }
  .card {
    align-self: stretch;
    border-radius: var(--br-3xs);
    background-color: var(--color-gray-200);
    border: 1px solid var(--color-gray-800);
    box-sizing: border-box;
    display: flex;
    flex-direction: row;
    align-items: flex-end;
    justify-content: space-between;
    padding: var(--padding-xs) var(--padding-lgi) var(--padding-2xs)
      var(--padding-sm);
    max-width: 100%;
    gap: var(--gap-xl);
    font-size: var(--font-size-mini);
    font-family: var(--font-poppins);
  }
  .complete-child {
    height: 42px;
    width: 333px;
    position: relative;
    border-radius: var(--br-3xs);
    background-color: var(--color-gray-300);
    display: none;
    max-width: 100%;
  }
  .complete-your-payment {
    position: relative;
    font-weight: 500;
    z-index: 1;
  }
  .payment-timer {
    position: relative;
    font-weight: 500;
    color: var(--color-red-200);
    display: inline-block;
    min-width: 37px;
    white-space: nowrap;
    z-index: 1;
  }
  .complete {
    align-self: stretch;
    border-radius: var(--br-3xs);
    background-color: var(--color-gray-300);
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: space-between;
    padding: var(--padding-smi) var(--padding-mini) var(--padding-smi)
      var(--padding-base);
    box-sizing: border-box;
    max-width: 100%;
    gap: var(--gap-xl);
    font-size: var(--font-size-smi);
    color: var(--color-gray-900);
  }
  .payment-method {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-base-1);
    max-width: 100%;
    text-align: center;
    font-size: var(--font-size-lg);
    color: var(--color-white);
  }
  .order-items {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-6xl);
    max-width: 100%;
  }
  .order-content {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-end;
    padding: 0px var(--padding-9xl) 0px var(--padding-11xl);
    box-sizing: border-box;
    max-width: 100%;
    text-align: left;
    font-size: var(--font-size-smi);
    color: var(--color-gray-700);
    font-family: var(--body-medium-regular);
  }
</style>
