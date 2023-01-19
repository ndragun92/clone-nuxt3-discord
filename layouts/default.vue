<template>
  <nav class="h-20 absolute top-0 left-0 right-0 z-10">
    <div class="h-full container flex items-center justify-between">
      <div>
        <nuxt-link to="/" class="relative">
          <SvgDiscord class="text-white" />
          <div class="absolute -top-2 -right-5 text-white font-bold text-xs">
            Clone
          </div>
        </nuxt-link>
      </div>
      <div>
        <ul class="flex items-center gap-10 font-semibold text-white">
          <li>
            <nuxt-link to="/download">Download</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/nitro">Nitro</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/discover">Discover</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/safety">Safety</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/support">Support</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/blog">Blog</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/careers">Careers</nuxt-link>
          </li>
        </ul>
      </div>
      <div>
        <nuxt-link to="/login" class="bg-white py-2.5 px-4 rounded-[1.250rem]"
          >Login</nuxt-link
        >
      </div>
    </div>
  </nav>
  <slot />
</template>

<script lang="ts">
import SvgDiscord from "~/components/svg/SvgDiscord.vue";

export default {
  name: "LayoutDefault",
  components: { SvgDiscord },
};
</script>

<style lang="scss" scoped>
ul {
  li {
    a {
      @apply hover:underline;
    }
  }
}
</style>
