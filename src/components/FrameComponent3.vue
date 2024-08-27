<template>
  <div class="avatar-parent">
    <img class="avatar-icon" loading="lazy" alt="" src="/avatar@2x.png" />
    <div class="frame-wrapper9">
      <div class="frame-parent11">
        <div class="puss-in-boots-the-last-wish-group">
          <h2 class="puss-in-boots3">Puss in boots the last wish</h2>
          <div class="action-adventure">Action, Adventure</div>
        </div>
        <button class="watch-trailer">
          <div class="watch-trailer-child" />
          <img class="watch-trailer-item" alt="" src="/polygon-1.svg" />
          <div class="watch-trailer1">Watch Trailer</div>
        </button>
      </div>
    </div>
    <div class="jake-sully-and-neytiri-have-f-wrapper">
      <h3 class="jake-sully-and">
        Jake Sully and Ney'tiri have formed a family and are doing everything to
        stay together. However, they must leave their home and explore the
        regions of Pandora. When an ancient threat resurfaces, Jake must fight a
        difficult war against the humans.
      </h3>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "FrameComponent3",
  });
</script>
<style scoped>
  .avatar-icon {
    align-self: stretch;
    position: relative;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
    object-fit: cover;
  }
  .puss-in-boots3 {
    margin: 0;
    position: relative;
    font-size: inherit;
    font-weight: 600;
    font-family: inherit;
  }
  .action-adventure {
    position: relative;
    font-size: var(--font-size-3xs);
    display: inline-block;
    min-width: 85px;
    z-index: 1;
  }
  .puss-in-boots-the-last-wish-group {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .watch-trailer-child {
    height: 22px;
    width: 84px;
    position: relative;
    border-radius: var(--br-8xs);
    background-color: var(--color-red-100);
    display: none;
  }
  .watch-trailer-item {
    height: 12px;
    width: 11px;
    position: relative;
    object-fit: contain;
    min-height: 12px;
    z-index: 1;
  }
  .watch-trailer1 {
    position: relative;
    font-size: var(--font-size-5xs);
    font-weight: 600;
    font-family: var(--font-poppins);
    color: var(--color-white);
    text-align: left;
    display: inline-block;
    min-width: 55px;
    z-index: 1;
  }
  .watch-trailer {
    cursor: pointer;
    border: none;
    padding: var(--padding-8xs) var(--padding-9xs);
    background-color: var(--color-red-100);
    width: 84px;
    border-radius: var(--br-8xs);
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    box-sizing: border-box;
    gap: var(--gap-7xs);
    white-space: nowrap;
  }
  .frame-parent11 {
    flex: 1;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: space-between;
    max-width: 100%;
    gap: var(--gap-xl);
  }
  .frame-wrapper9 {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-mid);
    box-sizing: border-box;
    max-width: 100%;
  }
  .jake-sully-and {
    margin: 0;
    flex: 1;
    position: relative;
    font-size: inherit;
    font-weight: 500;
    font-family: inherit;
    display: inline-block;
    max-width: 100%;
  }
  .jake-sully-and-neytiri-have-f-wrapper {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-6xl) 0px var(--padding-mid);
    box-sizing: border-box;
    max-width: 100%;
    font-size: var(--font-size-xs);
  }
  .avatar-parent {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-smi) var(--padding-10xs) 0px;
    box-sizing: border-box;
    gap: var(--gap-3xs);
    max-width: 100%;
    text-align: left;
    font-size: var(--font-size-mini);
    color: var(--color-white);
    font-family: var(--body-medium-regular);
  }
</style>
