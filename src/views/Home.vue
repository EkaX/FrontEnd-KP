<template>
  <div class="home">
    <HeaderArdilab />
    <HeroArdilab />
    <ProductsArdilab />
    <InstaArdilab />
    <PartnerArdilab />
    <FooterArdilab />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderArdilab from "@/components/HeaderArdilab.vue";
import HeroArdilab from "@/components/HeroArdilab.vue";
import ProductsArdilab from "@/components/ProductsArdilab.vue";
import InstaArdilab from "@/components/InstaArdilab.vue";
import PartnerArdilab from "@/components/PartnerArdilab.vue";
import FooterArdilab from "@/components/FooterArdilab.vue";

export default {
  name: "home",
  components: {
    HeaderArdilab,
    HeroArdilab,
    ProductsArdilab,
    InstaArdilab,
    PartnerArdilab,
    FooterArdilab
  }
};
</script>
