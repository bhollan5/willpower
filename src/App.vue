<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="scss">
@import '@/globalVars.scss';
#app {
  font-family: courier;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background: $black;
  color: $white;
  position: absolute;
  width: 100%;
  min-height: 100%;
  left: 0;
  top: 0;
}
</style>
