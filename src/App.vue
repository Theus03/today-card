<template>
  <div id="app">
    <Header msg="Olá, seja bem vindo!"/>
    <Slogan slogan="CADASTRE SEUS CARTÕES E DEIXE SUA VIDA FINANCEIRA MAIS ORGANIZADA."/>
    <Footer/>
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
    height: 350vh
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
</style>
