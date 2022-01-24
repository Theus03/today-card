<template>
  <div id="app">
    <Header msg="Olá, seja bem vindo!"/>
    <Slogan slogan="CADASTRE SEUS CARTÕES E DEIXE SUA VIDA FINANCEIRA MAIS ORGANIZADA."/>
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Slogan from './components/Slogan.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header, Slogan, Footer
  },

  methods: {
    nubank(){
      alert("laskdasd")
    }
  }
}
</script>

<style>
body {
  background-color: #000924;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: 'Poppins', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
}

@media (max-width: 800px) {
  #app {
    height: 370vh;
  }
  .logo {
    width: 5rem;
  }
  a, p {
    font-size: 0.5rem
  }

  .cards {
    flex-direction: column;
    align-items: center
  }
  .cards > div {
    margin: 0.5rem;
    padding: 0.5rem;
    height: 150px;
    
  }
}

@media (width: 820px){
  html {
    font-size: 0.8rem;
  }
}

@media (width: 912px){
  html {
    font-size: 0.8rem;
  }
}

@media (width: 1024px){
  #app {
    height: 410vh;
  }
}

@media (width: 1280px){
  html{
    font-size: 85.5%;
  }
  #app {
    width: 130vh;
  }
}
</style>
