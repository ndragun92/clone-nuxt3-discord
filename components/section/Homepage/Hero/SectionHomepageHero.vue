<template>
  <section class="relative bg-indigo-700">
    <div>
      <img
        src="/img/homepage/mountains.svg"
        alt=""
        class="absolute bottom-0 left-0 right-0"
      />
      <img
        src="/img/homepage/shoe.svg"
        alt=""
        class="absolute bottom-0 left-0"
      />
      <img
        src="/img/homepage/games.svg"
        alt=""
        class="absolute bottom-0 right-0"
      />
    </div>
    <div class="container">
      <div class="relative text-center py-40 text-white max-w-[780px] mx-auto">
        <h1 class="text-6xl font-black uppercase">Imagine a place...</h1>
        <p class="mt-10 text-xl">
          ...where you can belong to a school club, a gaming group, or a
          worldwide art community. Where just you and a handful of friends can
          spend time together. A place that makes it easy to talk every day and
          hang out more often.
        </p>
        <div class="actions mt-20">
          <a
            href="https://discord.com/api/downloads/distributions/app/installers/latest?channel=stable&platform=win&arch=x86"
            target="_blank"
            class="flex items-center gap-2 bg-white text-neutral-800"
          >
            <Icon size="28" name="material-symbols:download" />
            <span>Download for Windows</span>
          </a>
          <nuxt-link class="bg-neutral-800" to="/channels"
            >Open Discord in your browser</nuxt-link
          >
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.actions {
  @apply flex items-center justify-center gap-8;
  a {
    @apply font-medium;
    @apply py-4 px-8 rounded-[2rem];
  }
}
</style>
