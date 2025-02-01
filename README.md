<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¿Quieres ser mi Valentín?</title>
    <style>
        body {
            text-align: center;
            background-color: #ffebf0;
            font-family: Arial, sans-serif;
            color: #d63384;
        }
        .container {
            margin-top: 100px;
        }
        h1 {
            font-size: 36px;
        }
        .buttons {
            margin-top: 20px;
        }
        .btn {
            font-size: 20px;
            padding: 10px 20px;
            margin: 10px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
        }
        .yes {
            background-color: #ff4081;
            color: white;
        }
        .no {
            background-color: #ccc;
            color: black;
        }
        .yes:hover {
            background-color: #d81b60;
        }
        .no:hover {
            background-color: #999;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>💖 ¿Quieres ser mi Valentín? 💖</h1>
        <p>Hoy quiero preguntarte algo muy especial...</p>
        <div class="buttons">
            <button class="btn yes" onclick="aceptar()">✔️ Sí, me encantaría</button>
            <button class="btn no" onclick="rechazar()">💭 Déjame pensarlo...</button>
        </div>
        <p id="respuesta"></p>
    </div>

    <script>
        function aceptar() {
            document.getElementById("respuesta").innerHTML = "😍 ¡Sabía que dirías sí! Será un día increíble ❤️";
        }
        function rechazar() {
            document.getElementById("respuesta").innerHTML = "😢 Bueno... pero yo sé que en el fondo quieres decir sí 💕";
        }
    </script>
</body>
</html>
