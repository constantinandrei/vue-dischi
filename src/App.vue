<template>
  <div id="app" class="vh-100">
    <nav class="p-2">
      <div class="d-flex align-items-center justify-content-start">
          
        <img src="../public/logo-small.svg" alt="">
      </div>
    </nav>
    <div class="container">
      <div class="px-5 py-3">
        <div class="px-5">
          <TheMain/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import TheMain from './components/TheMain.vue'

export default {
  name: 'App',
  components: {
    TheMain
  }
}
</script>

<style lang="scss">
  nav {
    background-color: #2D3B46;

    img {
      max-width: 40px;
    }
  }

  #app {
    background-color: #1D2E3B;
    overflow: auto;
  }
</style>
