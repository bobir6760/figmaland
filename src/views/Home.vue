<template>
  <div class="home">
    <Navbar />
    <Best />
    <Features />
    <Fastest />
    <Partners />
    <Subscribe />
    <Pricing />
    <Contact />
    <Pages />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import Best from "@/components/Best.vue";
import Features from "@/components/Features.vue";
import Fastest from "@/components/Fastest.vue";
import Partners from "@/components/Partners.vue";
import Subscribe from "@/components/Subscribe.vue";
import Pricing from "@/components/Pricing.vue";
import Contact from "@/components/Contact.vue";
import Pages from "@/components/Pages.vue";
export default {
  name: "Home",
  components: {
    Navbar,
    Best,
    Features,
    Fastest,
    Partners,
    Subscribe,
    Pricing,
    Contact,
    Pages,
  },
};
</script>
<style lang="scss" scoped>
.home {
  position: relative;
}
</style>
