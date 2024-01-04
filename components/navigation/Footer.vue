<template>
  <div class="footer">
    <div class="container">
      <NuxtLink to="/" class="footer-brand">conduit</NuxtLink>
      <span class="footer-description">An interactive learning project from Thinkster. Code & design licensed under MIT.</span>
    </div>
    <div class="container">
      <span class="footer-content"
        ><NuxtLink :to="GITHUB_LINK" class="footer-content link">Real world app</NuxtLink>implementation using Nuxt v3 with Typescript and Composition Api.</span
      >
    </div>
  </div>
</template>
<style scoped>
@import url('~/assets/css/navigations/footer.scss');
</style>
