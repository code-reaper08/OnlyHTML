<template>
  <div class="main__wrapper">
    <div class="grid__container">
      <div class="left__container">
        <p class="primary__heading">Available for</p>
        <p class="norm__text">
          OnlyHTML browser extension is developed for both Chrome and Firefox,
          although Chrome version is not yet avaliable in the chrome web store
          <br />
          <br />
          Firefox add-on is successfully verified and available on the official
          Firefox add-on page
        </p>
      </div>
      <div class="right__container">
        <p class="primary__heading">Steps for using the extension</p>
        <p class="subtitle__text">For Firefox</p>
        <p class="norm__text">
          There are two ways for you to use the Firefox add-on,
          <br />
          <br />
          1. Adding to your browser from onlyhtml- Firefox add-on official site.
          <br />
          2. Manually installing using the .xpi file available in this
          repository.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionOne",
};
</script>

<style scoped>
/* for small screens */
@media (max-width: 576px) {
  .grid__container {
    display: grid;
    padding: 1rem 1rem;
    /* grid-template-rows: 1fr;
    grid-template-columns: 1fr; */
  }
  .left__container {
    width: 100%;
    /* display: flex; */
    margin-top: 2rem;
    /* flex-direction: column;
    align-items: unset;
    justify-self: center; */
  }
  .right__container {
    /* grid-column-start: 2;
    grid-row-start: 3; */
    /* width: 48.188rem;
    height: 30.438rem; */
    margin-top: 2rem;
  }
  .primary__heading {
    font-size: 36pt;
    padding-bottom: 2rem;
    color: var(--ternary-text-color);
  }
  .norm__text {
    font-size: 13.5pt;
    color: var(--subtitle-text-color);
  }
  .subtitle__text {
    font-size: 27pt;
    padding-bottom: 2rem;
    color: var(--button-bg-color);
  }
}
/* for large screens */
@media (min-width: 992px) {
  .grid__container {
    display: grid;
    padding: 1rem 2rem;
    grid-template-rows: 3fr 0fr 3fr;
    grid-template-columns: repeat(2, 1fr);
  }
  .left__container {
    width: 90%;
    display: flex;
    margin-top: 2rem;
    flex-direction: column;
    align-items: unset;
    /* justify-self: center; */
  }
  .right__container {
    grid-column-start: 2;
    grid-row-start: 3;
    width: 48.188rem;
    height: 30.438rem;
    margin-top: -12.5rem;
  }
  .primary__heading {
    font-size: 48pt;
    padding-bottom: 2rem;
    color: var(--ternary-text-color);
  }
  .norm__text {
    font-size: 18pt;
    color: var(--subtitle-text-color);
  }
  .subtitle__text {
    font-size: 27pt;
    padding-bottom: 2rem;
    color: var(--button-bg-color);
  }
}
</style>
