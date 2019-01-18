<template>
  <div id="home">
    <router-link tag="div" id="orb" to="/dash"></router-link>
    <h1>WILLPOWER</h1>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'home',
  components: {
  }
}
</script>

<style scoped lang="scss">
@import '@/globalVars.scss';

#orb {
  width: 300px;
  height: 300px;
  background: $white;
  border-radius: 50%;
  margin-bottom: 20px;
  cursor: pointer;
  transition-duration: .2s;
}
#orb:hover {
  transform: scale(1.1);
}
#home {
  padding-top: 20vh;
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>
