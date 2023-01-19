<template>
  <div>
    <SectionHomepageHero />
    <SectionHomepageServers />
    <SectionHomepageVoice />
    <SectionHomepageModeration />
  </div>
</template>

<script lang="ts">
import SectionHomepageHero from "~/components/section/Homepage/Hero/SectionHomepageHero.vue";
import SectionHomepageServers from "~/components/section/Homepage/Servers/SectionHomepageServers.vue";
import SectionHomepageVoice from "~/components/section/Homepage/Voice/SectionHomepageVoice.vue";
import SectionHomepageModeration from "~/components/section/Moderation/SectionHomepageModeration.vue";

export default {
  name: "PageHomepage",
  components: {
    SectionHomepageModeration,
    SectionHomepageVoice,
    SectionHomepageServers,
    SectionHomepageHero,
  },
};
</script>
