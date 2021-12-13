<template>
  <div id="app">

    <header>
      <Header/>
    </header>

    <main>
      <Main/>
    </main>

    <footer>

    </footer>

  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from '@/components/Main.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

header {
  position: relative;
  height: 600px;
  width: 100%;
  background-color: red;
  background-image: url("./assets/images/home-background-hero-scaled.jpg");
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
