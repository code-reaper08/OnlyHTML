<template>
  <div class="main__wrapper">
    <div class="main__container">
      <p class="primary__heading">
        Installing from the official Firefox add-on website
      </p>
      <ol class="list__group norm__text">
        <li>
          <p>
            Head over
            <a
              target="_blank"
              href="https://addons.mozilla.org/en-US/firefox/addon/onlyhtml/"
              >[here]</a
            >
            using Firefox.
          </p>
        </li>
        <li>
          <p>Click on <strong>Add to Firefox</strong> Button.</p>
        </li>
        <img src="@/assets/image1.png" alt="add-on page image" />
        <li>Now the add-on is successfully added to your browser.</li>
        <img src="@/assets/image2.png" alt="extension-icon" />
        <li>
          To use the add-on click on the icon shown in <strong>step 3</strong>,
          when viweing a webpage.
        </li>
        <li>Voila! All <strong>CSS</strong> removed.</li>
        <li>
          To have the <strong>CSS</strong> back, click on the same icon again.
        </li>
        <li>Alright have some <strong>FUN!</strong></li>
      </ol>
    </div>
  </div>
</template>
<script>
export default {
  name: "SectionTwo",
};
</script>

<style scoped>
/* for small screens */
@media (max-width: 576px) {
}
/* for large screens */
@media (min-width: 992px) {
  .main__wrapper {
    width: 56.5rem;
    padding: 1rem 3rem;
  }
  .list__group {
    padding-left: 3rem;
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
  img {
    margin: 1rem 0rem 0rem -2.7rem;
  }
}
</style>
