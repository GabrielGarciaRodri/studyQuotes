<template>
  <div class="ticket">
    <img class="notch-icon2" alt="" src="/notch@2x.png" />
    <img
      class="recording-indicator-icon2"
      alt=""
      src="/recording-indicator.svg"
    />
    <section class="ticket-inner">
      <div class="frame-parent1">
        <FrameComponent6 />
        <div class="movie-info">
          <div class="rectangle-parent">
            <div class="frame-item" />
            <div class="details">
              <div class="movie-title">
                <div class="title">
                  <img
                    class="title-background-icon"
                    loading="lazy"
                    alt=""
                    src="/rectangle-387@2x.png"
                  />
                  <div class="movie-name">
                    <h3 class="puss-in-boots">Puss In Boots The Last Wish</h3>
                  </div>
                </div>
                <div class="entrance-info">
                  <div class="show-this-ticket">
                    Show this ticket at the entrance
                  </div>
                </div>
              </div>
            </div>
            <div class="cinema-info">
              <div class="cinema-details">
                <div class="cinema-details-child" />
                <div class="location-date">
                  <div class="cinema-location">
                    <div class="location-name">
                      <div class="cinema-parent">
                        <b class="cinema1">Cinema</b>
                        <h3 class="hartono-mall-12">Hartono Mall 12</h3>
                      </div>
                    </div>
                    <div class="date-time-cost">
                      <div class="date-time-cost-values">
                        <b class="date">Date</b>
                        <b class="sun-feb">Sun , Feb 12th 2023</b>
                      </div>
                      <div class="date-time-cost-values">
                        <b class="cinema-hall">Cinema Hall #</b>
                        <b class="cinema-a">Cinema A</b>
                      </div>
                      <div class="date-time-cost-values">
                        <b class="cost">Cost</b>
                        <b class="b">$26,99</b>
                      </div>
                    </div>
                  </div>
                  <div class="seat-order">
                    <img
                      class="seat-order-background"
                      loading="lazy"
                      alt=""
                      src="/rectangle-376@2x.png"
                    />
                    <div class="seat-order-details">
                      <div class="seat-order-info">
                        <div class="date-time-cost-values">
                          <b class="time">Time</b>
                          <b class="b1">13:00 </b>
                        </div>
                        <div class="date-time-cost-values">
                          <b class="cost">Seat</b>
                          <b class="c5">C5</b>
                        </div>
                        <div class="seat-order-values2">
                          <b class="order-id">Order ID</b>
                          <div class="div">12345678</div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="line-parent">
              <div class="frame-inner" />
              <div class="barcode-container">
                <img
                  class="barcode-icon"
                  loading="lazy"
                  alt=""
                  src="/barcode.svg"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <div class="home-indicator4">
      <div class="home-indicator5" />
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";
  import FrameComponent6 from "./FrameComponent6.vue";

  export default defineComponent({
    name: "Ticket",
    components: { FrameComponent6 },
  });
</script>
<style scoped>
  .notch-icon2 {
    width: 219px;
    height: 30px;
    position: relative;
    object-fit: cover;
    display: none;
  }
  .recording-indicator-icon2 {
    width: 6px;
    height: 6px;
    position: relative;
    display: none;
  }
  .frame-item {
    align-self: stretch;
    height: 620px;
    position: relative;
    border-radius: var(--br-xl);
    background-color: var(--color-white);
    display: none;
  }
  .title-background-icon {
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
  .puss-in-boots {
    margin: 0;
    position: relative;
    font-size: inherit;
    font-weight: 700;
    font-family: inherit;
    z-index: 1;
  }
  .movie-name {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 0px 0px var(--padding-9xs);
  }
  .title {
    align-self: stretch;
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-7xs);
  }
  .show-this-ticket {
    position: relative;
    z-index: 1;
  }
  .entrance-info {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-9xs);
    font-size: var(--font-size-smi);
    color: var(--color-gray-100);
  }
  .movie-title {
    align-self: stretch;
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .details {
    align-self: stretch;
    height: 174px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-end;
    padding: 0px var(--padding-lgi) var(--padding-8xs) var(--padding-4xl);
    box-sizing: border-box;
  }
  .cinema-details-child {
    align-self: stretch;
    height: 1px;
    position: relative;
    border-top: 1px solid var(--color-gainsboro);
    box-sizing: border-box;
    z-index: 1;
  }
  .cinema1 {
    position: relative;
    display: inline-block;
    min-width: 54px;
    z-index: 1;
  }
  .hartono-mall-12 {
    margin: 0;
    position: relative;
    font-size: var(--font-size-xl);
    text-transform: uppercase;
    font-weight: 700;
    font-family: inherit;
    color: var(--color-black);
    z-index: 2;
    margin-top: -3px;
  }
  .cinema-parent {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .location-name {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 0px 0px var(--padding-12xs);
  }
  .date {
    position: relative;
    display: inline-block;
    min-width: 32px;
    z-index: 1;
  }
  .sun-feb {
    position: relative;
    font-size: var(--font-size-mini);
    color: var(--color-black);
    z-index: 1;
  }
  .date-time-cost-values {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-6xs);
  }
  .cinema-hall {
    position: relative;
    display: inline-block;
    min-width: 97px;
    z-index: 1;
  }
  .cinema-a {
    position: relative;
    font-size: var(--font-size-mini);
    display: inline-block;
    color: var(--color-black);
    min-width: 76px;
    z-index: 1;
  }
  .cost {
    position: relative;
    display: inline-block;
    min-width: 31px;
    z-index: 1;
  }
  .b {
    position: relative;
    font-size: var(--font-size-mini);
    display: inline-block;
    color: var(--color-black);
    min-width: 51px;
    white-space: nowrap;
    z-index: 1;
  }
  .date-time-cost {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-lgi);
  }
  .cinema-location {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-23xl-5);
  }
  .seat-order-background {
    width: 47px;
    height: 48px;
    position: relative;
    border-radius: var(--br-8xs);
    object-fit: cover;
    z-index: 1;
  }
  .time {
    position: relative;
    display: inline-block;
    min-width: 34px;
    z-index: 1;
  }
  .b1 {
    position: relative;
    font-size: var(--font-size-mini);
    display: inline-block;
    color: var(--color-black);
    min-width: 39px;
    white-space: nowrap;
    z-index: 1;
  }
  .c5 {
    position: relative;
    font-size: var(--font-size-mini);
    display: inline-block;
    color: var(--color-black);
    min-width: 22px;
    z-index: 1;
  }
  .order-id {
    position: relative;
    display: inline-block;
    min-width: 55px;
    z-index: 1;
  }
  .div {
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
  .seat-order-values2 {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-6xs);
  }
  .seat-order-info {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-lgi);
  }
  .seat-order-details {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-end;
    padding: 0px var(--padding-5xs) 0px 0px;
  }
  .seat-order {
    width: 86px;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    justify-content: flex-start;
    gap: var(--gap-23xl);
  }
  .location-date {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-end;
    justify-content: flex-start;
    gap: var(--gap-mini);
  }
  .cinema-details {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-smi);
  }
  .cinema-info {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-end;
    padding: 0px var(--padding-lgi) 0px var(--padding-4xl);
    font-size: var(--font-size-smi);
    color: var(--color-gray-100);
  }
  .frame-inner {
    align-self: stretch;
    height: 0.5px;
    position: relative;
    border-top: 0.5px dashed var(--color-black);
    box-sizing: border-box;
    z-index: 1;
  }
  .barcode-icon {
    height: 49px;
    width: 267px;
    position: relative;
    z-index: 1;
  }
  .barcode-container {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-10xl);
  }
  .line-parent {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-base-5);
  }
  .rectangle-parent {
    flex: 1;
    border-radius: var(--br-xl);
    background-color: var(--color-white);
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    justify-content: flex-start;
    padding: var(--padding-7xl) 0px var(--padding-xl);
    box-sizing: border-box;
    gap: 21px;
    max-width: 100%;
  }
  .movie-info {
    width: 327px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-12xs);
    box-sizing: border-box;
    max-width: 100%;
  }
  .frame-parent1 {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 0px 0px var(--padding-12xs);
    box-sizing: border-box;
    gap: 50px;
    max-width: 100%;
  }
  .ticket-inner {
    width: 379px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-end;
    padding: 0px var(--padding-lgi);
    box-sizing: border-box;
    max-width: 100%;
    text-align: left;
    font-size: var(--font-size-xl);
    color: var(--color-black);
    font-family: var(--font-poppins);
  }
  .home-indicator5 {
    height: 5px;
    width: 134px;
    position: relative;
    border-radius: var(--br-81xl);
    background-color: var(--color-white);
  }
  .home-indicator4 {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: center;
    padding: var(--padding-mid) var(--padding-xl) var(--padding-5xs)
      var(--padding-2xl);
  }
  .ticket {
    width: 393px;
    background-color: var(--color-gray-500);
    max-width: 100%;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    justify-content: flex-start;
    padding: var(--padding-6xs) 0px 0px;
    box-sizing: border-box;
    gap: 67px;
    line-height: normal;
    letter-spacing: normal;
  }
</style>
