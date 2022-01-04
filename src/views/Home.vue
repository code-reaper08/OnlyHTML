<template>
  <div class="home">
    <!-- Header component -->
    <Header />
    <!-- Main title component -->
    <MainTitle />
    <!-- Button group component -->
    <ButtonBlock />
    <!-- Footer component -->
    <Footer />
  </div>
</template>
<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import MainTitle from "@/components/MainTitle.vue";
import ButtonBlock from "@/components/ButtonBlock.vue";
import Footer from "@/components/Footer.vue";
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
