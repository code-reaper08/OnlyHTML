<template>
  <div class="main__wrapper">
    <div class="main__container">
      <p class="primary__heading">Installing using the .xpi file</p>
      <p class="norm__text">
        To install the add-on using the .xpi file, follow the below steps.
      </p>
      <ol class="list__group norm__text">
        <li>
          In
          <a target="_blank" href="https://github.com/code-reaper08/OnlyHTML/"
            >[this]</a
          >
          repository navigate to <code>Firfox/onlyhtml-1.0-fx.xpi</code> or
          click
          <a
            target="_blank"
            href="https://github.com/code-reaper08/OnlyHTML/blob/main/Firefox/onlyhtml-1.0-fx.xpi"
            >[here]</a
          >.
        </li>
        <li>Click on the <strong>Download</strong> button.</li>
        <img id="dwnld__btn" src="@/assets/image3.png" alt="download-button" />
        <li>
          Open <strong>Add-ons and Themes</strong> menu or press
          <strong><code>Ctrl+Shift+A</code></strong>
        </li>
        <img src="@/assets/image4.png" alt="menu-screenshot" />
        <li>
          Click on gear icon and Install
          <strong>Add-on from file...</strong> option inside menu.
        </li>
        <img
          src="@/assets/image5.png"
          alt="Add-on from file option in the menu"
        />
        <li>
          Select the <strong>.xpi</strong> file, downloaded in
          <strong>Step 2</strong>.
        </li>
        <li>
          Click on <strong>Add</strong> and <strong>Okay</strong> in the
          subsequent prompts.
        </li>
        <li>Now you can use the add-on normally.</li>
      </ol>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionThree",
};
</script>

<style scoped>
/* for small screens */
@media (max-width: 576px) {
  .main__wrapper {
    margin-top: 5rem;
    /* width: 56.5rem; */
    padding: 1rem 1rem;
  }
  .list__group {
    padding-left: 3rem;
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
  img {
    margin: 1rem 0rem 0rem -2.7rem;
    width: 100%;
  }
  #dwnld__btn {
    width: 50%;
  }
  code {
    background: darkslategray;
    padding: 0.2rem;
  }
}
/* for large screens */
@media (min-width: 992px) {
  .main__wrapper {
    margin-top: 10rem;
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
  code {
    background: darkslategray;
    padding: 0.2rem;
  }
}
</style>
