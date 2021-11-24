<template>
  <div id="app">
   <Header />
   <Main />
   <Merchandise />
  </div>
</template>

<script>

import Header from "./components/Header.vue"
import Main from "./components/Main.vue"
import Merchandise from "./components/Merchandise.vue"

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Merchandise
  },
 
}
</script>

<style lang="scss">
  @import "./assets/style/generals.scss";

</style>
