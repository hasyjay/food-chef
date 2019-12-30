<template>
  <div>
   <Header/>
   <Mainpage/>
   <Footer/>
    
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Mainpage from './components/Mainpage.vue'
import Footer from './components/Footer.vue'

export default {
  
  name: 'app',
  components: {
    Header,
    Mainpage,
    Footer
  }
}
</script>

<style>

</style>
