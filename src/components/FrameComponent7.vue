<template>
  <div class="info-movie-inner">
    <div class="frame-parent10">
      <header class="frame-header">
        <div class="left-side-group">
          <img
            class="left-side-icon2"
            loading="lazy"
            alt=""
            src="/left-side.svg"
          />
          <div class="frame-wrapper8">
            <div class="mobile-signal-group">
              <img
                class="mobile-signal-icon2"
                loading="lazy"
                alt=""
                src="/mobile-signal.svg"
              />
              <img class="wifi-icon2" loading="lazy" alt="" src="/wifi.svg" />
              <img
                class="battery-icon2"
                loading="lazy"
                alt=""
                src="/battery.svg"
              />
            </div>
          </div>
        </div>
      </header>
      <div class="arrow-right-container">
        <img
          class="arrow-right-icon2"
          loading="lazy"
          alt=""
          src="/arrowright@2x.png"
        />
        <a class="order-summary">Order Summary</a>
        <div class="more">
          <img
            class="more-vertical-icon2"
            loading="lazy"
            alt=""
            src="/morevertical.svg"
          />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "FrameComponent7",
  });
</script>
<style scoped>
  .left-side-icon2 {
    height: 21px;
    width: 54px;
    position: relative;
  }
  .mobile-signal-icon2 {
    height: 10.7px;
    width: 17px;
    position: relative;
  }
  .wifi-icon2 {
    height: 11px;
    width: 15.3px;
    position: relative;
  }
  .battery-icon2 {
    align-self: stretch;
    width: 24.3px;
    position: relative;
    max-height: 100%;
    min-height: 11px;
  }
  .mobile-signal-group {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-8xs);
  }
  .frame-wrapper8 {
    width: 66.6px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-end;
    padding: 0px 0px var(--padding-8xs-4);
    box-sizing: border-box;
  }
  .left-side-group {
    flex: 1;
    display: flex;
    flex-direction: row;
    align-items: flex-end;
    justify-content: space-between;
    max-width: 100%;
    gap: var(--gap-xl);
  }
  .frame-header {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 0px 0px var(--padding-12xs);
    box-sizing: border-box;
    max-width: 100%;
  }
  .arrow-right-icon2 {
    height: 24px;
    width: 24px;
    position: relative;
    overflow: hidden;
    flex-shrink: 0;
    object-fit: contain;
  }
  .order-summary {
    text-decoration: none;
    position: relative;
    font-weight: 600;
    color: inherit;
    white-space: nowrap;
  }
  .more-vertical-icon2 {
    width: 24px;
    height: 24px;
    position: relative;
    overflow: hidden;
    flex-shrink: 0;
  }
  .more {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-11xs) 0px 0px;
  }
  .arrow-right-container {
    width: 327px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: space-between;
    max-width: 100%;
    gap: var(--gap-xl);
  }
  .frame-parent10 {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-12xl);
    max-width: 100%;
  }
  .info-movie-inner {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-12xs) 0px var(--padding-10xs);
    box-sizing: border-box;
    max-width: 100%;
    text-align: center;
    font-size: var(--font-size-lg);
    color: var(--color-white);
    font-family: var(--body-medium-regular);
  }
</style>
