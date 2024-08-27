<template>
  <section class="movie-details1">
    <div class="frame-parent16">
      <div class="puss-in-boots-the-last-wrapper">
        <h2 class="puss-in-boots5">puss in boots the last...</h2>
      </div>
      <div class="frame-parent17">
        <div class="adventure-wrapper">
          <div class="adventure1">Adventure</div>
        </div>
        <div class="movie-status">
          <div class="status-items">
            <h2 class="coming-soon">Coming soon</h2>
          </div>
          <div class="slider">
            <div class="slider-indicator">
              <div class="indicator-items" />
              <div class="indicator-items" />
              <div class="active-indicator" />
              <div class="indicator-items" />
              <div class="indicator-items" />
            </div>
          </div>
          <div class="status-items1">
            <a class="see-all1">See all</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "MovieDetails",
  });
</script>
<style scoped>
  .puss-in-boots5 {
    margin: 0;
    position: relative;
    font-size: inherit;
    text-transform: capitalize;
    font-weight: 600;
    font-family: inherit;
  }
  .puss-in-boots-the-last-wrapper {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-40xl) 0px var(--padding-41xl);
  }
  .adventure1 {
    position: relative;
    text-transform: capitalize;
    font-weight: 600;
    display: inline-block;
    min-width: 66px;
  }
  .adventure-wrapper {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: center;
    padding: 0px var(--padding-2xl) 0px var(--padding-xl);
  }
  .coming-soon {
    margin: 0;
    position: relative;
    font-size: inherit;
    font-weight: 600;
    font-family: inherit;
    display: inline-block;
    min-width: 115px;
  }
  .status-items {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-14xl) 0px 0px;
  }
  .indicator-items {
    height: 8px;
    width: 8px;
    position: relative;
    border-radius: 50%;
    background-color: var(--color-white);
  }
  .active-indicator {
    height: 8px;
    width: 24px;
    position: relative;
    border-radius: var(--br-9xs);
    background-color: var(--color-red-100);
  }
  .slider-indicator {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-12xs);
    gap: var(--gap-9xs);
  }
  .slider {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    min-width: 94px;
  }
  .see-all1 {
    text-decoration: none;
    position: relative;
    font-weight: 600;
    color: inherit;
    display: inline-block;
    min-width: 45px;
  }
  .status-items1 {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-19xl) 0px 0px;
    font-size: var(--body-medium-regular-size);
    color: var(--color-red-100);
  }
  .movie-status {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: center;
    flex-wrap: wrap;
    align-content: flex-start;
    gap: var(--gap-sm);
    font-size: var(--font-size-lg);
    color: var(--color-white);
  }
  .frame-parent17 {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-mini);
    font-size: var(--font-size-smi);
    color: var(--color-gray-700);
  }
  .frame-parent16 {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-2xs);
    max-width: 100%;
  }
  .movie-details1 {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-end;
    padding: 0px var(--padding-11xl);
    box-sizing: border-box;
    max-width: 100%;
    text-align: left;
    font-size: var(--font-size-lg);
    color: var(--color-white);
    font-family: var(--body-medium-regular);
  }
</style>
