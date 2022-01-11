<template>
  <div class="usageinfo">
    <!-- Header component -->
    <Header />
    <!-- Section one component -->
    <SectionOne />
    <!-- Section two component -->
    <SectionTwo />
  </div>
</template>
<script>
import Header from "@/components/Usageinfo/Header.vue";
import SectionOne from "@/components/Usageinfo/SectionOne.vue";
import SectionTwo from "@/components/Usageinfo/SectionTwo.vue";
export default {
  name: "Usageinfo",
  components: {
    Header,
    SectionOne,
    SectionTwo,
  },
};
</script>
<style scoped></style>
