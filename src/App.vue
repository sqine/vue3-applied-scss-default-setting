<template>
  <router-view />
</template>

<style lang="scss">
@import "@/assets/styles/_default.scss";

#app {
  background: #{$bg-color};
  font-family: #{$font-family-default}, sans-serif;
  @include fontSet;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
