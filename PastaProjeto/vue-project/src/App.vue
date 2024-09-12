<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="cabecalho">
      <img src="../src/assets/img/Logo.png" alt=""> 
    </div>
    <div>
      <nav>
        <a href="/" class="router-link-exact-active router-link-active">Home</a>
        <a href="/cadastro">Cadastro</a>
        <a href="/login">Login</a>
      </nav>
    </div>
  </header>

  <RouterView />
 
    <footer>
  
    </footer>
    
</template>

<style scoped>
*{
  font-family: Arial, Helvetica, sans-serif;
}
header {
  height:130px;
  background-color: rgba(43, 121, 195, 1);
}
footer{
  background-color: rgba(43, 121, 195, 1);
  height: 130px;
  width: 100%;
  display: block;
  padding-top: 0%;
  margin-top: 0%;
  border: none;
}
nav{
  margin-left: 350px;
}

a{
  text-decoration: none;
  color:aliceblue;
  font-size: 20px;
  padding: 5px;
}
.logo {
  display: block;
  margin: 0 auto 2rem;
}

.cabecalho{
padding: 10px;
width: 194;
height: 70px;
}

</style>
