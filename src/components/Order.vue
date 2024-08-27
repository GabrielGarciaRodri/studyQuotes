<template>
  <div class="order">
    <img class="notch-icon" alt="" src="/notch@2x.png" />
    <img
      class="recording-indicator-icon"
      alt=""
      src="/recording-indicator.svg"
    />
    <section class="info-movie">
      <FrameComponent7 />
      <div class="info-movie-child" />
      <FrameComponent8 />
    </section>
    <section class="order-details">
      <OrderContent />
      <div class="actions">
        <div class="buy-button">
          <button class="buy">
            <div class="buy-child" />
            <div class="buy-ticket">Buy ticket</div>
          </button>
        </div>
        <div class="home-indicator">
          <div class="home-indicator1" />
        </div>
      </div>
    </section>
  </div>
</template>
<script>
  import { defineComponent } from "vue";
  import FrameComponent7 from "./FrameComponent7.vue";
  import FrameComponent8 from "./FrameComponent8.vue";
  import OrderContent from "./OrderContent.vue";

  export default defineComponent({
    name: "Order",
    components: { FrameComponent7, FrameComponent8, OrderContent },
  });
</script>
<style scoped>
  .notch-icon {
    width: 219px;
    height: 30px;
    position: relative;
    object-fit: cover;
    display: none;
  }
  .recording-indicator-icon {
    width: 6px;
    height: 6px;
    position: relative;
    display: none;
  }
  .info-movie-child {
    width: 100%;
    height: 100%;
    position: absolute;
    margin: 0 !important;
    top: 0px;
    right: 0px;
    bottom: 0px;
    left: 0px;
    background: linear-gradient(58.52deg, #272727, rgba(39, 39, 39, 0));
  }
  .info-movie {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-6xs) var(--padding-lgi) var(--padding-22xl)
      var(--padding-11xl);
    box-sizing: border-box;
    position: relative;
    gap: 35px;
    max-width: 100%;
    z-index: 1;
  }
  .buy-child {
    height: 53px;
    width: 333px;
    position: relative;
    border-radius: var(--br-3xs);
    background-color: var(--color-red-100);
    display: none;
    max-width: 100%;
  }
  .buy-ticket {
    width: 117.5px;
    position: relative;
    font-size: var(--font-size-base);
    font-weight: 600;
    font-family: var(--body-medium-regular);
    color: var(--color-white);
    text-align: center;
    display: inline-block;
    flex-shrink: 0;
    z-index: 1;
  }
  .buy {
    cursor: pointer;
    border: none;
    padding: var(--padding-mid) var(--padding-xl);
    background-color: var(--color-red-100);
    flex: 1;
    border-radius: var(--br-3xs);
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: center;
    box-sizing: border-box;
    white-space: nowrap;
    max-width: 100%;
  }
  .buy-button {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-11xl);
    box-sizing: border-box;
    max-width: 100%;
  }
  .home-indicator1 {
    height: 5px;
    width: 134px;
    position: relative;
    border-radius: var(--br-81xl);
    background-color: var(--color-white);
  }
  .home-indicator {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: center;
    padding: var(--padding-mid) var(--padding-xl) var(--padding-5xs)
      var(--padding-2xl);
  }
  .actions {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-xl);
    max-width: 100%;
  }
  .order-details {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    justify-content: flex-start;
    gap: 69px;
    max-width: 100%;
  }
  .order {
    width: 393px;
    background-color: var(--color-gray-500);
    max-width: 100%;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-xl);
    line-height: normal;
    letter-spacing: normal;
  }
</style>
