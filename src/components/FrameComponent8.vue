<template>
  <div class="rectangle-parent11">
    <img
      class="frame-child25"
      loading="lazy"
      alt=""
      src="/rectangle-5632@2x.png"
    />
    <div class="movie-details">
      <div class="title1">
        <a class="puss-in-boots-container">
          <p class="wish">puss in boots the last</p>
          <p class="wish">Wish</p>
        </a>
        <a class="adventure">Adventure</a>
      </div>
      <div class="location">
        <div class="hartono-mall">HARTONO MALL</div>
        <div class="sun-12-feb">Sun, 12 Feb 2023. 13:00</div>
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "FrameComponent8",
  });
</script>
<style scoped>
  .frame-child25 {
    height: 143px;
    width: 112px;
    position: relative;
    border-radius: var(--br-3xs);
    object-fit: cover;
    z-index: 1;
  }
  .wish {
    margin: 0;
  }
  .puss-in-boots-container {
    text-decoration: none;
    position: relative;
    text-transform: capitalize;
    font-weight: 600;
    color: inherit;
    z-index: 1;
  }
  .adventure {
    text-decoration: none;
    position: relative;
    font-size: var(--font-size-smi);
    text-transform: capitalize;
    font-weight: 600;
    color: var(--color-gray-700);
    display: inline-block;
    min-width: 66px;
    z-index: 1;
  }
  .title1 {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-8xs);
  }
  .hartono-mall {
    position: relative;
    text-transform: capitalize;
    font-weight: 600;
    display: inline-block;
    min-width: 114px;
    z-index: 1;
  }
  .sun-12-feb {
    position: relative;
    font-size: var(--font-size-smi);
    text-transform: capitalize;
    font-weight: 600;
    color: var(--color-gray-700);
    white-space: nowrap;
    z-index: 1;
  }
  .location {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-3xs);
    font-size: var(--body-medium-regular-size);
    color: var(--color-white);
  }
  .movie-details {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-6xl);
    min-width: 180px;
  }
  .rectangle-parent11 {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: center;
    padding: 0px var(--padding-xl) 0px 0px;
    box-sizing: border-box;
    gap: var(--gap-mini);
    max-width: 100%;
    text-align: left;
    font-size: var(--font-size-base);
    color: var(--color-red-100);
    font-family: var(--body-medium-regular);
  }
</style>
