<template>
  <div class="frame-wrapper11">
    <div class="cinema-container">
      <h1 class="cinema4">Cinema</h1>
      <div class="cinemas-container">
        <div class="atrium">
          <div class="atrium-child" />
          <h2 class="atrium-cinemas">Atrium Cinemas</h2>
          <div class="staff-lines-saddar-karachi-wrapper">
            <div class="staff-lines-saddar">Staff Lines, Saddar, Karachi</div>
          </div>
          <img
            class="atrium-item"
            loading="lazy"
            alt=""
            src="/rectangle-3761@2x.png"
          />
        </div>
        <div class="neuplex">
          <div class="neuplex-child" />
          <h2 class="neuplex1">
            <p class="neuplex2">Neuplex</p>
          </h2>
          <div class="khayaban-e-shaheen-dha-phas-wrapper">
            <div class="staff-lines-saddar">
              Khayaban - e Shaheen, Dha Phase 8
            </div>
          </div>
          <img
            class="atrium-item"
            loading="lazy"
            alt=""
            src="/rectangle-377@2x.png"
          />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "FrameComponent5",
  });
</script>
<style scoped>
  .cinema4 {
    margin: 0;
    position: relative;
    font-size: inherit;
    font-weight: 600;
    font-family: inherit;
    display: inline-block;
    min-width: 59px;
  }
  .atrium-child {
    height: 59px;
    width: 337px;
    position: relative;
    border-radius: var(--br-3xs);
    background-color: var(--color-gray-200);
    border: 2px solid var(--color-red-100);
    box-sizing: border-box;
    display: none;
    max-width: 100%;
    z-index: 1;
  }
  .atrium-cinemas {
    margin: 0;
    position: relative;
    font-size: inherit;
    font-weight: 600;
    font-family: inherit;
    display: inline-block;
    min-width: 112px;
    z-index: 1;
  }
  .staff-lines-saddar {
    position: relative;
    font-weight: 300;
    z-index: 1;
  }
  .staff-lines-saddar-karachi-wrapper {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-xl) 0px 0px;
    margin-left: -112px;
    font-size: var(--font-size-3xs);
  }
  .atrium-item {
    height: 48px;
    width: 48.3px;
    position: absolute;
    margin: 0 !important;
    right: 19.5px;
    bottom: 3px;
    border-radius: var(--br-8xs);
    object-fit: cover;
    z-index: 1;
  }
  .atrium {
    align-self: stretch;
    height: 59px;
    border-radius: var(--br-3xs);
    background-color: var(--color-gray-200);
    border: 2px solid var(--color-red-100);
    box-sizing: border-box;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-4xs) var(--padding-smi) var(--padding-2xs);
    position: relative;
    max-width: 102%;
    flex-shrink: 0;
  }
  .neuplex-child {
    height: 55px;
    width: 333px;
    position: relative;
    border-radius: var(--br-3xs);
    background-color: var(--color-gray-200);
    display: none;
    max-width: 100%;
    z-index: 1;
  }
  .neuplex2 {
    margin: 0;
  }
  .neuplex1 {
    margin: 0;
    position: relative;
    font-size: inherit;
    font-weight: 600;
    font-family: inherit;
    display: inline-block;
    min-height: 40px;
    z-index: 1;
  }
  .khayaban-e-shaheen-dha-phas-wrapper {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-xl) 0px 0px;
    margin-left: -55.5px;
    font-size: var(--font-size-3xs);
  }
  .neuplex {
    align-self: stretch;
    border-radius: var(--br-3xs);
    background-color: var(--color-gray-200);
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-4xs) var(--padding-smi) var(--padding-7xs);
    box-sizing: border-box;
    position: relative;
    max-width: 100%;
  }
  .cinemas-container {
    align-self: stretch;
    height: 120px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-3xs);
    max-width: 100%;
    font-size: var(--font-size-smi);
    font-family: var(--font-poppins);
  }
  .cinema-container {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-mini);
    max-width: 100%;
  }
  .frame-wrapper11 {
    width: 367px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-mid);
    box-sizing: border-box;
    max-width: 100%;
    text-align: left;
    font-size: var(--font-size-base);
    color: var(--color-white);
    font-family: var(--body-medium-regular);
  }

  @media screen and (max-width: 450px) {
    .cinemas-container {
      height: 120px;
    }
  }
</style>
