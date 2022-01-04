<template>
  <div class="footer__container">
    <div class="footer__wrapper">
      <p class="footer__content">Made with [love!] by</p>
      <span class="gh-profile-link"> <a href="#">code-reaper08</a></span>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
/* for small screens */
@media (max-width: 576px) {
  .footer__wrapper {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .footer__container {
    margin-top: 3vh;
    font-size: 13.5pt;
  }
  .gh-profile-link {
    margin-left: 0.5rem;
  }
  .footer__content {
    color: var(--subtitle-text-color);
  }
}

/* for large screens */
@media (min-width: 992px) {
  .footer__wrapper {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
  }
  .footer__container {
    margin-top: 20vh;
    font-size: 18pt;
  }
  .footer__content {
    color: var(--subtitle-text-color);
  }
  .gh-profile-link {
    margin-left: 0.5rem;
  }
}
</style>
