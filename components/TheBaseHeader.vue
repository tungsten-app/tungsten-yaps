<template>
  <header>
    <div class="base-layout__wrapper">
      <nuxt-link to="/">
        <img src="" alt="Tungsten logo" itemprop="logo" />
      </nuxt-link>
      <nav>
        <ul>
          <li><nuxt-link to="/features">Features</nuxt-link></li>
          <li><nuxt-link to="/about">About</nuxt-link></li>
          <li><nuxt-link to="/login">Sign in stupid</nuxt-link></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style lang="scss" scoped>
@use '../assets/styles/mixins' as *;

.router-link-active {
  color: rgb(159, 106, 7);
}

.base-layout__wrapper {
  @include flex-layout(null, space-between, center);
}

ul {
  @include flex-layout(null, center, center);
  column-gap: 1rem;
}
</style>