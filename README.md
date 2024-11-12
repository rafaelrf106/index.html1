<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="index.css">
    <title>Chamado</title>
    <style>
body{
    font-family: Arial, Helvetica, sans-serif;
    background-image: linear-gradient(50deg, rgba(41, 40, 40, 0.336), rgb(78, 77, 77));
}
div{
    background-color: rgba(0, 0, 0, 0.3);
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    padding: 80px;
    border-radius: 15px;
    color: whitesmoke;
}
input{
padding: 25px;
border: none;
outline: none;
font-size: 25px;

}
button{
    background-color: dodgerblue;
    border: none;
    padding: 25px;
    width: 100%;
    border-radius: 25px;
    color:  white;
    font-size: 20px;
    cursor: pointer;
}
    button:hover{
        background-color: deepskyblue;
    }
    </style>
</head>
<body>
    <div>
        <img src="c:\Users\USUARIO GAMER\Downloads\logo-GLPI-250-black.png" alt="logo do GLPI">
        <h1>Chamado</h1>
        <input type="text" placeholder="Nome do Equipamento:">
        <br> <br>
        <input type="text" placeholder="Local:">
        <br> <br>
        <input type="text" placeholder="Problema:">
        <br> <br>
        <button>ENVIAR</button>
    </div>
</body>
</html>
