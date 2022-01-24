<template>
  <div class="home">
    <nav>
      <p>{{msg}}</p>
      <img class="logo" src="../assets/logo.png" alt="Logo - Today's Card">
      <a href="">Ir para os meus cartões</a>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

nav {
  display:flex;
  align-items: center;
  justify-content: space-around;
  padding: 0
}

.logo {
  width: 12rem;
}

a {
  color: #fff;
}

</style>
