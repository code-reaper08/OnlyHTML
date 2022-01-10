<template>
  <div class="home">
    <!-- Header component -->
    <div class="header__container">
      <Header />
    </div>
    <!-- Main title component -->
    <div class="maintitle__container">
      <MainTitle />
    </div>
    <!-- Button group component -->
    <div class="button__grp__container">
      <ButtonBlock />
    </div>
    <!-- Footer component -->
    <div class="footer__container">
      <Footer />
    </div>
  </div>
</template>
<script>
// @ is an alias to /src
import Header from "@/components/Homepage/Header.vue";
import MainTitle from "@/components/Homepage/MainTitle.vue";
import ButtonBlock from "@/components/Homepage/ButtonBlock.vue";
import Footer from "@/components/Homepage/Footer.vue";
export default {
  name: "Home",
  components: {
    Header,
    MainTitle,
    ButtonBlock,
    Footer,
  },
};
</script>
<style scoped>
.home {
  height: 100vh;
  padding: 0.5rem 1rem 0rem 1rem;
  display: flex;
  flex-direction: column;
}
</style>
