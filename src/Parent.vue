<template>
<div>
    <Header/>
    <Body/>
    <Portfolio/>
    <About/>
    <Contact/>
    <Footer/>
</div>
</template>



<script>
import Header from './components/Header.vue'
import Body from './components/Body.vue'
import Portfolio from './components/Portfolio.vue'
import About from './components/About.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'
export default {
  components:{
    Header,
    Body,
    Portfolio,
    About,
    Contact,
    Footer
  } 
  
}
</script>