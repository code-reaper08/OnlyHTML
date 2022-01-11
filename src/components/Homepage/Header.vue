<template>
  <div class="header__wrapper">
    <div class="button__container">
      <a
        href="https://github.com/code-reaper08/OnlyHTML/tree/main"
        target="_blank"
      >
        <button>
          <div class="text__content">
            <p>[Star] & [Fork]</p>
          </div>
          <div class="icon__container">
            <img src="@/assets/gh-icon.png" alt="github-icon" />
          </div>
        </button>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
/* for small screens */
@media (max-width: 576px) {
  .header__wrapper {
    display: flex;
  }
  button {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
    font-size: 9.75pt;
    width: 10.688rem;
    height: 2.461rem;
    cursor: pointer;
  }
  .icon__container > img {
    width: 1.758rem;
    height: auto;
  }
}
/* for large screens */
@media (min-width: 992px) {
  .header__wrapper {
    display: flex;
    justify-content: end;
  }
  button {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
    font-size: 18pt;
    width: 19rem;
    height: 4rem;
    cursor: pointer;
  }
}
</style>
