<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <BannerShayna />
    <IGShayna />
    <LogoShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroShayna from "@/components/HeroShayna.vue";
import BannerShayna from "@/components/BannerShayna.vue";
import IGShayna from "@/components/IGShayna.vue";
import LogoShayna from "@/components/LogoShayna.vue";
import FooterShayna from "@/components/FooterShayna.vue";

export default {
  name: "Home",
  components: {
    HeaderShayna,
    HeroShayna,
    BannerShayna,
    IGShayna,
    LogoShayna,
    FooterShayna,
  },
};
</script>
