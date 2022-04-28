<template>
  <div>
    <div id="header-hero" class="base-layout__wrapper">
      <h2>Tungsten</h2>
      <p>The quickest way to do your mom. And to do everyone's mom!</p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use '../assets/styles/mixins' as *;

#header-hero {
  @include flex-layout(column, center, center);
}

h2 {
  font-size: 2.5rem;
  font-weight: 700;
  margin: 0;
}

p {
  font-size: 1.5rem;
  margin: 0;
}
</style>
