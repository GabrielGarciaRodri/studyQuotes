<template>
  <div class="frame-parent12">
    <div class="frame-parent13">
      <div class="left-side-wrapper">
        <img
          class="left-side-icon3"
          loading="lazy"
          alt=""
          src="/left-side.svg"
        />
      </div>
      <img
        class="arrow-right-icon3"
        loading="lazy"
        alt=""
        src="/arrowright@2x.png"
      />
    </div>
    <div class="ticket-details">
      <a class="ticket2">Ticket</a>
    </div>
    <div class="connection-wrapper">
      <div class="connection">
        <img
          class="mobile-signal-icon3"
          loading="lazy"
          alt=""
          src="/mobile-signal.svg"
        />
        <div class="wifi-battery-parent">
          <div class="connection">
            <img class="wifi-icon3" loading="lazy" alt="" src="/wifi.svg" />
            <img
              class="battery-icon3"
              loading="lazy"
              alt=""
              src="/battery.svg"
            />
          </div>
          <div class="more1">
            <img
              class="more-vertical-icon3"
              loading="lazy"
              alt=""
              src="/morevertical.svg"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "FrameComponent6",
  });
</script>
<style scoped>
  .left-side-icon3 {
    height: 21px;
    width: 54px;
    position: relative;
  }
  .left-side-wrapper {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 0px 0px var(--padding-12xs);
  }
  .arrow-right-icon3 {
    width: 24px;
    height: 24px;
    position: relative;
    overflow: hidden;
    flex-shrink: 0;
    object-fit: contain;
  }
  .frame-parent13 {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-12xl);
  }
  .ticket2 {
    text-decoration: none;
    align-self: stretch;
    position: relative;
    font-weight: 600;
    color: inherit;
    display: inline-block;
    min-width: 55px;
  }
  .ticket-details {
    width: 55px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-33xl) 0px 0px;
    box-sizing: border-box;
  }
  .mobile-signal-icon3 {
    height: 10.7px;
    width: 17px;
    position: relative;
  }
  .wifi-icon3 {
    height: 11px;
    width: 15.3px;
    position: relative;
    flex-shrink: 0;
  }
  .battery-icon3 {
    align-self: stretch;
    width: 24.3px;
    position: relative;
    max-height: 100%;
    min-height: 11px;
    flex-shrink: 0;
  }
  .more-vertical-icon3 {
    height: 24px;
    width: 24px;
    position: relative;
    overflow: hidden;
    flex-shrink: 0;
  }
  .more1 {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-smi) 0px var(--padding-6xs);
  }
  .wifi-battery-parent {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-18xl-4);
  }
  .connection {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-8xs);
  }
  .connection-wrapper {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-7xs-3) 0px 0px;
  }
  .frame-parent12 {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: space-between;
    gap: var(--gap-xl);
    text-align: center;
    font-size: var(--font-size-lg);
    color: var(--color-white);
    font-family: var(--body-medium-regular);
  }
</style>
