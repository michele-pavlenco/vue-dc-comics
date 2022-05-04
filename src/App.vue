<template>
  <div id="app">
<HeaderContent/>
<MainContent/>
<FooterContent/>


    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
import HeaderContent from './components/HeaderContent.vue' 
import MainContent from './components/MainContent.vue' 
//import FooterContent from './components/FooterContent.vue' 

import FooterContent from './components/FooterContent.vue'

export default {
  name: 'App',
  components: {
    MainContent,
    HeaderContent,
    FooterContent

  }
}
</script>

<style lang="scss">
.container{
  width: 80%;
  margin: 0 auto;
}
</style>
