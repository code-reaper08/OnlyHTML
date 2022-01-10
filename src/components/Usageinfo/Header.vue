<template>
  <div class="header__wrapper">
    <div class="header__container">
      <div class="left__title">
        <div class="title__and__version">
          <h1 class="main__title">OnlyHTML</h1>
          <span class="version__no">v1.0.0</span>
        </div>
      </div>
      <div class="right__button">
        <div class="button__container">
          <button>
            <div class="text__content">
              <p>[Star] & [Fork]</p>
            </div>
            <div class="icon__container">
              <img src="@/assets/gh-icon.png" alt="github-icon" />
            </div>
          </button>
        </div>
      </div>
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
  .header__container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    padding: 0.5rem 1rem;
  }
  .title__and__version {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: center;
  }
  .main__title {
    font-size: 36pt;
    color: var(--primary-text-color);
  }
  .version__no {
    font-size: 18pt;
    color: var(--ternary-text-color);
  }
  button {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
    font-size: 18pt;
    width: 19rem;
    height: 4rem;
  }
}
/* for large screens */
@media (min-width: 992px) {
  .header__container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    padding: 0.5rem 1rem;
  }
  .title__and__version {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: center;
  }
  .main__title {
    font-size: 36pt;
    color: var(--primary-text-color);
  }
  .version__no {
    font-size: 18pt;
    color: var(--ternary-text-color);
  }
  button {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
    font-size: 18pt;
    width: 19rem;
    height: 4rem;
  }
}
</style>
