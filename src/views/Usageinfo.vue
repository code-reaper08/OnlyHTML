<template>
  <div class="usageinfo">
    <!-- Header component -->
    <Header />
    <!-- Section one component -->
    <SectionOne />
  </div>
</template>
<script>
import Header from "@/components/Usageinfo/Header.vue";
import SectionOne from "@/components/Usageinfo/SectionOne.vue";
export default {
  name: "Usageinfo",
  components: {
    Header,
    SectionOne,
  },
};
</script>
<style scoped></style>
