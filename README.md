<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Integración de Páginas Web</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        .button-container {
            margin-top: 20px;
        }
 
        button {
            margin: 10px;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
        }

        iframe {
            width: 90%;
            height: 600px;
            margin-top: 20px;
            border: 1px solid #ccc;
        }

        footer {
            margin-top: 30px;
            background-color: #f2f2f2;
            padding: 12px;
            font-size: 15px;
            color: #333;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <h1>Explora las siguientes páginas</h1>

    <div class="button-container">
        <button onclick="cargarPagina('file:///C:/Users/bel-s208-lt-013.UMD/Downloads/esencia%20glam%20maquillaje%20(1).html')">Formulario</button>
        <button onclick="cargarPagina('file:///C:/Users/bel-s208-lt-013.UMD/Downloads/juego%20de%20memoria%20(1).html')">Juego</button>
        <button onclick="cargarPagina('file:///C:/Users/bel-s208-lt-013.UMD/Downloads/manuela%20florez%20ramirez%20y%20mariajose%20duque%20(4).html')">Principal</button>
    </div>

    <iframe id="visor" src="" title="Visor de páginas"></iframe>

    <footer>
        <p>Elaborado por: <strong>Maria Jose Duque y Manuela Florez</strong></p>
    </footer>

    <script>
        function cargarPagina(url) {
            document.getElementById('visor').src = url;
        }
    </script>

</body>
</html>
