<template>
<form action="cadastro">
  
<div id="main">
    <h1>Cadastro</h1>
   <div class="entrada">
    <input type="text"  placeholder="Nome Completo:" for="nome">
<input type="text" placeholder="Data Nascimento: dd/mm/aaaa" for="data">
<input type="text" placeholder="Idade:" for="idade">
<input type="text" placeholder="Sexo:" for="sexo">
<input type="text" placeholder="Mãe ou Responsável:" for="responsavel">
<input type="text" placeholder="Endereço:" for="endereço">
<input type="text" placeholder="Complemento" for="complemento">
<input type="text" placeholder="Numero:" for="numero">
<input type="text" placeholder="Cidade:" for="cidade">
<input type="text" placeholder="UF:" for="uf">
<input type="text" placeholder="Bairro:" for="bairro">
<input type="text" placeholder="Telefone" for="telefone">
<input type="text" placeholder="Celular" for="celular">
<input type="text" placeholder="Email" for="email">
   </div>
  
</div>
</form>
</template>

<style scoped>
* {
    margin: 0;
    padding: 0;
    font-family: Arial, Helvetica, sans-serif;
}
#main h1{
    color:#2B79C3;
    margin-bottom: 40px;
    margin-left: 40%;
    margin-top: 30px;
}
#main {
    margin-left: 20%;
    margin-top: 2%;
    margin-bottom: 2%;
    width: 915px;
    height: 579px;
    background-color: #F0F0F0;
    border-style: none;
    border-radius: 20px;
   
    padding: 20px;
 ;
}
.entrada input {
justify-content:right;
margin-bottom: 5px;
margin-top: 5px;
background-color: #E4E4E4;
border: 2px solid #3B4651;
border-radius: 5px;
padding: 5px;
margin-left: 10px;
}
.entrada input:nth-child(1){
    width: 800px;
}
.entrada input:nth-child(2){
    width: 500px;
   
}
.entrada input:nth-child(3){
    width: 80px;
   
}
.entrada input:nth-child(4){
    width: 120px;
  
}
.entrada input:nth-child(5){
    width: 800px;
   
}
.entrada input:nth-child(6){
    width: 800px;
   
}
.entrada input:nth-child(7){
    width: 600px;
  
}
.entrada input:nth-child(8){
    width: 200px;
   
}
.entrada input:nth-child(9){
    width: 500px;
   
}
.entrada input:nth-child(10){
    width: 100px;
  
}
.entrada input:nth-child(11){
    width: 200px;
  
}.entrada input:nth-child(12){
    width: 400px;
    
}.entrada input:nth-child(13){
    width: 400px;
  
}
.entrada input:nth-child(14){
    width: 800px;
   
}
</style>