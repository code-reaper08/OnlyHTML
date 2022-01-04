<template>
  <div class="block__wrapper">
    <div class="button__grp__wrapper">
      <div class="button__container">
        <button>Add to Firefox</button>
      </div>
      <div class="button__container">
        <button>How to use</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ButtonBlock",
};
</script>

<style scoped>
/* for small screens */
@media (max-width: 576px) {
  .block__wrapper {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    margin-top: 2rem;
  }
  .button__grp__wrapper {
    display: flex;
    height: 10.844rem;
    flex-direction: column;
    justify-content: space-evenly;
    align-items: center;
  }
  button {
    width: 11.625rem;
    height: 2.969rem;
    font-size: 13.5pt;
    font-family: "Source Code Pro", monospace;
  }
}

/* for large screens */
@media (min-width: 992px) {
  .block__wrapper {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    margin-top: 2rem;
  }
  .button__grp__wrapper {
    display: flex;
    width: 37.125rem;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
  }
  button {
    width: 14.438rem;
    height: 3.688rem;
    font-size: 18pt;
    font-family: "Source Code Pro", monospace;
  }
}
</style>
