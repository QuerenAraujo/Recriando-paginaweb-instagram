# Recriando-paginaweb-instagram
Desafio da Dio, recriando a página web do instagram com html e css.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, user-scalable=yes, initial-scale=1.0, maximum-scale=10, minimum-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Instagram</title>
</head>
<body>
    <div class="instagram-wrapper">
        <div class="instagram-phone">
          <img src="./img/-bd5-Iphone.png" alt="celular">  
    </div>
    <div class="instagram-continue">
<div class="group">
    <img src="./img/logo.png" class="instagram-logo" alt="instagram-log">
    <div class="profile-photo">
        <img src="./img/foto-instagram.jpeg" alt="Foto de Perfil">

    </div>
    <a href="s" class="instagram-login">Continue como queren.araujo</a>
    <a href="s" class="instagram-logout">Remover Conta</a>
</div>
<div class="group">
    <p class="not-acount">Não é queren.araujo?</p>
    <p class="not-acount">
       <span class="link-blue">Alternar contar</span> 
       ou 
       <span class="link-blue">Inscreva-se</span>
    </p>
</div>
<div class="get-the-app">
    <p class="get-the">Baixe o aplicativo</p>
    <div class="download">
        <a href="S" class="app-download"></a>
        <a href="S" class="app-download"></a>
    </div>
</div>
    </div>
</body>
</html>

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    text-decoration: none;
    font-family: sans-serif;
    font-size: 14px;

}

body{
width: 100%;
min-height: 100vh;
background-color: rgb(#243, #243, #2433);
margin: 0;
padding: 0;
display: flex;
justify-content: center;

 }

 .instagram-wrapper{
    display: flex;
    align-items: center;
    justify-content: start;
    width: 60%;
    height: 100vh;
 }

 .instagram-phone{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 50%;
 }
 .instagram-phone img {
    height: 50rem;
 }
.profile-photo{
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50%;
    overflow: hidden;
}
 .profile-photo img {
    height:100px;
    width: 100px;
 }

 .instagram-continue {
    display: flex;
    align-items: center;
    justify-content: space-around;
    flex-direction: column;
    width: 50%;
    min-height: 34rem;
 }

 .group {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background-color: #fff;
    width: 100%;
    padding: 1.3rem 0;
    border: 1px solid lightgray;
 }

 .group:nth-child(1){
    min-width: 19rem;

 }

 .instagram-logo{
    height: 5rem;
 }

 .instagram-login {
    background-color: #0095e6;
    color: #fff;
    padding: 8px;
    border-radius: 4px;
    margin-top: 2rem;

 }

 .instagram-logout{
    color: #0095e6;
    margin-top: 1rem;

 }

 .not-acount{
    color: rgb(#160, #160, #160);

 }

 .link-blue{
    color: #0095e6;
 }
 .get-the-app{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
    padding: 1.3rem 0;
 }

 .download{
    display: flex;
    width: 100%;
    justify-content: space-evenly;
    align-items: center;
    padding: 1rem;

 }

 .app-download{
    height: 3rem;
    width: 10rem;
    background-size: cover;
 }

 .app-download:nth-child(1){
    background-image: url(./img/disponivel-na-app-store-botao-1.png);
 }
 
 .app-download:nth-child(2){
    background-image: url(./img/disponivel-google-play-badge-1.png);

 }

 /* media queries */

 @media (max-widht: 1024px) {
    .instagram-wrapper{
        width: 90%;
     }

 }

 @media (max-widht: 650px) {
    body{
        background-color: #fff;
    }
    .instagram-wrapper{
        width: 90%;
    }

    .instagram-phone{
        display: none;
    }

    .instagram-continue{
        width: 100%;
    }
 }



