<template>
  <v-app>
   <Nav />

    <v-main class="main">
      <v-container fill-height class="elem-container">
        <v-layout row justify-center align-center>
            <v-flex sm6 class="content">
              <HelloWorld/>
            </v-flex>
            <v-flex sm6 class="content">
              <About/>
            </v-flex>
        </v-layout>
      </v-container>
      

    </v-main>
    <Footer />
  </v-app>
</template>

<script>
import Nav from './components/Nav'
import HelloWorld from './components/HelloWorld'
import About from './components/About'
import Footer from './components/Footer'


export default {
  name: 'App',

  components: {
    Nav,
    HelloWorld,
    About,
    Footer
  },

  data: () => ({
    //
  })
}
</script>

<style>
 .main {
   height: 100%;
   max-height: 100%;
   overflow-y: hidden;
   background-color: yellow;
 }

 .elem-container {
   width: 100%;
   max-width: 100%;
 }


  @media screen and (max-width: 600px) {
   .main {
     height: auto;
   }
  }
</style>
