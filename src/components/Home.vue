<template>
  <div class="home">
    <img class="notch-icon3" alt="" src="/notch@2x.png" />
    <img
      class="recording-indicator-icon3"
      alt=""
      src="/recording-indicator.svg"
    /><FrameComponent1 />
    <div class="movie-list">
      <div class="now-playing-parent">
        <h2 class="now-playing">Now playing</h2>
        <div class="see-all-button">
          <a class="see-all">See all</a>
        </div>
      </div>
    </div>
    <section class="movie-posters">
      <div class="poster-list">
        <img
          class="poster-items-icon"
          loading="lazy"
          alt=""
          src="/rectangle-4170@2x.png"
        />
        <img
          class="poster-items-icon1"
          loading="lazy"
          alt=""
          src="/rectangle-4172@2x.png"
        />
        <img
          class="poster-items-icon2"
          loading="lazy"
          alt=""
          src="/rectangle-4171@2x.png"
        />
      </div>
    </section>
    <MovieDetails />
    <section class="upcoming-movies">
      <UpcomingMovieItem /><GroupComponent1 />
    </section>
  </div>
</template>
<script>
  import { defineComponent } from "vue";
  import FrameComponent1 from "./FrameComponent1.vue";
  import MovieDetails from "./MovieDetails.vue";
  import UpcomingMovieItem from "./UpcomingMovieItem.vue";
  import GroupComponent1 from "./GroupComponent1.vue";

  export default defineComponent({
    name: "Home",
    components: {
      FrameComponent1,
      MovieDetails,
      UpcomingMovieItem,
      GroupComponent1,
    },
  });
</script>
<style scoped>
  .notch-icon3 {
    width: 219px;
    height: 30px;
    position: relative;
    object-fit: cover;
    display: none;
  }
  .recording-indicator-icon3 {
    width: 6px;
    height: 6px;
    position: relative;
    display: none;
  }
  .now-playing {
    margin: 0;
    position: relative;
    font-size: inherit;
    font-weight: 600;
    font-family: inherit;
    display: inline-block;
    min-width: 108px;
  }
  .see-all {
    text-decoration: none;
    position: relative;
    font-weight: 600;
    color: inherit;
    display: inline-block;
    min-width: 45px;
  }
  .see-all-button {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-8xs) 0px 0px;
    font-size: var(--body-medium-regular-size);
    color: var(--color-red-100);
  }
  .now-playing-parent {
    flex: 1;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: space-between;
    max-width: 100%;
    gap: var(--gap-xl);
  }
  .movie-list {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-end;
    padding: 0px var(--padding-11xl) var(--padding-xl);
    box-sizing: border-box;
    max-width: 100%;
  }
  .poster-items-icon {
    position: absolute;
    height: 100%;
    top: 0px;
    bottom: 0px;
    left: 94px;
    border-radius: var(--br-xl);
    max-height: 100%;
    width: 204px;
    object-fit: cover;
  }
  .poster-items-icon1 {
    position: absolute;
    height: 100%;
    top: 0px;
    bottom: 0px;
    left: -130px;
    border-radius: var(--br-xl);
    max-height: 100%;
    width: 204px;
    object-fit: cover;
  }
  .poster-items-icon2 {
    position: absolute;
    height: 100%;
    top: 0px;
    bottom: 0px;
    left: 318px;
    border-radius: var(--br-xl);
    max-height: 100%;
    width: 204px;
    object-fit: cover;
  }
  .poster-list {
    height: 319px;
    flex: 1;
    position: relative;
    overflow-x: auto;
    max-width: 100%;
  }
  .movie-posters {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 0px var(--padding-xs);
    box-sizing: border-box;
    max-width: 100%;
  }
  .upcoming-movies {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    max-width: 100%;
  }
  .home {
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
    gap: var(--gap-3xs);
    line-height: normal;
    letter-spacing: normal;
    text-align: left;
    font-size: var(--font-size-lg);
    color: var(--color-white);
    font-family: var(--body-medium-regular);
  }
</style>
