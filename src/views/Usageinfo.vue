<template>
  <div class="usageinfo">
    <!-- Header component -->
    <Header />
    <!-- Section one component -->
    <SectionOne />
    <!-- Section two component -->
    <SectionTwo />
    <!-- Section three component -->
    <SectionThree />
    <!-- Footer component -->
    <Footer class="footer__component" />
  </div>
</template>
<script>
import Header from "@/components/Usageinfo/Header.vue";
import SectionOne from "@/components/Usageinfo/SectionOne.vue";
import SectionTwo from "@/components/Usageinfo/SectionTwo.vue";
import SectionThree from "@/components/Usageinfo/SectionThree.vue";
import Footer from "@/components/Homepage/Footer.vue";
export default {
  name: "Usageinfo",
  components: {
    Header,
    SectionOne,
    SectionTwo,
    SectionThree,
    Footer,
  },
};
</script>
<style scoped>
.footer__component {
  padding-bottom: 2rem;
}
</style>
