<template>
  <div class="frame-wrapper10">
    <div class="cast-parent">
      <h1 class="cast">Cast</h1>
      <div class="cast-container">
        <div class="cast-images">
          <img
            class="cast-images-child"
            loading="lazy"
            alt=""
            src="/ellipse-208@2x.png"
          />
          <div class="names-wrapper">
            <div class="names">
              <div class="antonio-banderas">Antonio Banderas</div>
              <div class="roles-container">
                <div class="puss-in-boots4">Puss in Boots</div>
              </div>
            </div>
          </div>
        </div>
        <div class="cast-images">
          <img class="cast-images-child" alt="" src="/ellipse-208-1@2x.png" />
          <div class="names-wrapper">
            <div class="names">
              <div class="salma-hayek">Salma Hayek</div>
              <div class="kitty-softpaws-wrapper">
                <div class="kitty-softpaws">Kitty Softpaws</div>
              </div>
            </div>
          </div>
        </div>
        <div class="cast-images">
          <img class="cast-images-child" alt="" src="/ellipse-208-2@2x.png" />
          <div class="names-wrapper">
            <div class="names">
              <div class="harvey-guilln">Harvey Guillén</div>
              <div class="perro-wrapper">
                <div class="perro2">Perro</div>
              </div>
            </div>
          </div>
        </div>
        <div class="cast-images3">
          <img class="cast-images-child" alt="" src="/ellipse-208-2@2x.png" />
          <div class="harvey-guilln-wrapper">
            <div class="harvey-guilln1">Harvey Guillén</div>
          </div>
        </div>
        <img class="cast-container-child" alt="" src="/ellipse-208-2@2x.png" />
        <div class="harvey-guilln-container">
          <div class="harvey-guilln2">Harvey Guillén</div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "FrameComponent4",
  });
</script>
<style scoped>
  .cast {
    margin: 0;
    position: relative;
    font-size: inherit;
    font-weight: 600;
    font-family: inherit;
    display: inline-block;
    min-width: 36px;
  }
  .cast-images-child {
    height: 41px;
    width: 41px;
    position: relative;
    border-radius: 50%;
    object-fit: cover;
  }
  .antonio-banderas {
    position: relative;
    font-weight: 600;
    display: inline-block;
    min-width: 73px;
    flex-shrink: 0;
  }
  .puss-in-boots4 {
    margin-top: -1px;
    position: relative;
    font-weight: 300;
    display: inline-block;
    min-width: 51px;
    flex-shrink: 0;
    z-index: 1;
  }
  .roles-container {
    height: 11px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-3xl) 0px 0px;
    box-sizing: border-box;
  }
  .names {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .names-wrapper {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-end;
    padding: 0px 0px var(--padding-6xs);
  }
  .cast-images {
    display: flex;
    flex-direction: row;
    align-items: flex-end;
    justify-content: flex-start;
    padding: 0px var(--padding-5xs) 0px 0px;
    gap: var(--gap-8xs);
    flex-shrink: 0;
  }
  .salma-hayek {
    position: relative;
    font-weight: 600;
    display: inline-block;
    min-width: 54px;
    flex-shrink: 0;
  }
  .kitty-softpaws {
    margin-top: -1px;
    position: relative;
    font-weight: 300;
    display: inline-block;
    min-width: 56px;
    flex-shrink: 0;
    z-index: 1;
  }
  .kitty-softpaws-wrapper {
    height: 11px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 0px 0px;
    box-sizing: border-box;
  }
  .harvey-guilln {
    position: relative;
    font-weight: 600;
    display: inline-block;
    min-width: 60px;
    flex-shrink: 0;
  }
  .perro2 {
    margin-top: -1px;
    position: relative;
    font-weight: 300;
    display: inline-block;
    min-width: 21px;
    flex-shrink: 0;
    z-index: 1;
  }
  .perro-wrapper {
    height: 11px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-xl) 0px 0px;
    box-sizing: border-box;
  }
  .harvey-guilln1 {
    align-self: stretch;
    position: relative;
    font-weight: 600;
  }
  .harvey-guilln-wrapper {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-2xs) 0px 0px;
  }
  .cast-images3 {
    width: 114px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-5xs) 0px 0px;
    box-sizing: border-box;
    gap: var(--gap-8xs);
    flex-shrink: 0;
  }
  .cast-container-child {
    height: 41px;
    width: 41px;
    position: relative;
    border-radius: 50%;
    object-fit: cover;
    min-height: 41px;
    flex-shrink: 0;
  }
  .harvey-guilln2 {
    align-self: stretch;
    position: relative;
    font-weight: 600;
    flex-shrink: 0;
  }
  .harvey-guilln-container {
    width: 60px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-2xs) 0px 0px;
    box-sizing: border-box;
    flex-shrink: 0;
  }
  .cast-container {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-8xs);
    font-size: var(--font-size-5xs);
    font-family: var(--font-poppins);
  }
  .cast-parent {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-mini);
    max-width: 100%;
  }
  .frame-wrapper10 {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 0px var(--padding-6xs) var(--padding-mid);
    box-sizing: border-box;
    max-width: 100%;
    text-align: left;
    font-size: var(--font-size-base);
    color: var(--color-white);
    font-family: var(--body-medium-regular);
  }
</style>
