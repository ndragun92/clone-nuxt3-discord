<template>
  <div>
    <SectionHomepageHero />
    <SectionHomepageServers />
  </div>
</template>

<script lang="ts">
import SectionHomepageHero from "~/components/section/Homepage/Hero/SectionHomepageHero.vue";
import SectionHomepageServers from "~/components/section/Homepage/Servers/SectionHomepageServers.vue";

export default {
  name: "PageHomepage",
  components: { SectionHomepageServers, SectionHomepageHero },
};
</script>
