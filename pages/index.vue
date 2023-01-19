<template>
  <div>
    <SectionHomepageHero />
    <SectionHomepageServers />
    <SectionHomepageVoice />
  </div>
</template>

<script lang="ts">
import SectionHomepageHero from "~/components/section/Homepage/Hero/SectionHomepageHero.vue";
import SectionHomepageServers from "~/components/section/Homepage/Servers/SectionHomepageServers.vue";
import SectionHomepageVoice from "~/components/section/Homepage/Voice/SectionHomepageVoice.vue";

export default {
  name: "PageHomepage",
  components: {
    SectionHomepageVoice,
    SectionHomepageServers,
    SectionHomepageHero,
  },
};
</script>
