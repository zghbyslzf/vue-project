<template>
  <div id="app" class="app">
    <router-view />
  </div>
</template>

<style lang="scss">
@import "@/styles/normalize.scss";
html,
body {
  @include vw();
}
.app {
  @include flexCenter();
}
</style>
