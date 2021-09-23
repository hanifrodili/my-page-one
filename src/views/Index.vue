<template lang="pug">
  .page-one
    navbar
    top-section
    brand-banner
    features-section
    testimoni-section
    solutions-section
    cta-banner
    my-footer
</template>
<script>
import Navbar from '@/components/Navbar.vue'
import TopSection from '@/components/TopSection.vue'
import BrandBanner from '@/components/BrandBanner.vue'
import FeaturesSection from '@/components/FeaturesSection.vue'
import TestimoniSection from '@/components/TestimoniSection.vue'
import SolutionsSection from '@/components/SolutionsSection.vue'
import CtaBanner from '@/components/CtaBanner.vue'
import MyFooter from '@/components/Footer.vue'
export default {
  name: "PageOne",
  components: {
    Navbar,
    TopSection,
    BrandBanner,
    FeaturesSection,
    TestimoniSection,
    SolutionsSection,
    CtaBanner,
    MyFooter
  }
}
</script>
<style scoped>
 @import '../assets/css/page-one.css';
</style>
