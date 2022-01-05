<template>
  <div class="main__wrapper">
    <div class="title__and__version">
      <h1 class="main__title">OnlyHTML</h1>
      <span class="version__no">v1.0.0</span>
    </div>
    <div class="subtitle">
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum ex
        quibusdam error amet atque
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainTitle",
};
</script>

<style scoped>
/* for small screens */
@media (max-width: 576px) {
  .main__wrapper {
    margin-top: 15vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
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
  .subtitle {
    margin-top: 1rem;
    width: 20.75rem;
    text-align: center;
  }
  .subtitle > p {
    color: var(--subtitle-text-color);
    font-size: 13.5pt;
    line-height: 30.17px;
  }
}

/* for large screens */
@media (min-width: 992px) {
  .main__wrapper {
    margin-top: 20vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .title__and__version {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: center;
  }
  .main__title {
    font-size: 40.5pt;
    color: var(--primary-text-color);
  }
  .version__no {
    font-size: 18pt;
    color: var(--ternary-text-color);
  }
  .subtitle {
    margin-top: 1rem;
    width: 25.75rem;
    text-align: center;
  }
  .subtitle > p {
    color: var(--subtitle-text-color);
    font-size: 18pt;
    line-height: 30.17px;
  }
}
</style>
