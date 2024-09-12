<template>


    <div id="main">
        <img src="../assets/img/login.png" alt="login">
        <input type="text" placeholder="Usuário">
        <input type="password" placeholder="Senha">
        <span>esqueci minha senha</span>
        <button>Entrar</button>
        <p>Não tem cadastro?</p>
        <button><a href="/cadastro">Cadastre-se</a></button>
    </div>

</template>
<style scoped>
* {
    margin: 0;
    padding: 0;
    font-family: Arial, Helvetica, sans-serif;
}

#main {
    margin-left: 40%;
    margin-top: 2%;
    margin-bottom: 2%;
    width: 420px;
    height: 550px;
    background-color: #C8DFF0;
    border: 2px solid #2B79C3;
    border-radius: 20px;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 20px;
    display: flex;
    flex-direction: column;
}

#main input {

    margin-bottom: 20px;
    margin-top: 20px;
    background-color: #B1BCC7;
    border: 2px solid #3B4651;
    border-radius: 5px;
    padding: 5px;
    width: 420px;
    height: 30px;
}

#main span {
    margin-left: 260px;
    color: #2B79C3;
    margin-top: -10px;
    margin-bottom: 20px;
    display: block;
}

#main p {
    color: #2B79C3;
    margin-top: 30px;
    margin-bottom: 20px;
    display: block;
}

#main button {
    color: #E4E4E4;
    width: 420px;
    height: 50px;
    background-color: #2B79C3;
    border: 2px solid #2B79C3;
    border-radius: 20px;
    display: block;
}

#main button a {
    text-decoration: none;
    color: #E4E4E4;
}
</style>