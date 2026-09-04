<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galería de Instrumentos Musicales</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #222;
        }

        /* ENCABEZADO */
        header {
            height: 146px;
            background-color: #222;
            color: white;
            text-align: center;
            padding-top: 27px;
        }

        header h1 {
            font-size: 22px;
            margin-bottom: 7px;
        }

        header p {
            font-size: 10px;
            font-weight: bold;
        }

        /* GALERÍA */
        .galeria {
            width: 800px;
            margin: 27px auto;
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 16px;
        }

        /* TARJETAS */
        .instrumento {
            background-color: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 3px 7px rgba(0, 0, 0, 0.15);
            text-align: center;
        }

        /* PARTE SUPERIOR */
        .imagen {
            height: 145px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
        }

        .imagen h2 {
            font-size: 42px;
            font-weight: normal;
        }

        /* COLORES */
        .guitarra {
            background-color: #333333;
        }

        .piano {
            background-color: #246abd;
        }

        .bateria {
            background-color: #683bb5;
        }

        .violin {
            background-color: #ed1760;
        }

        .saxofon {
            background-color: #ff9900;
        }

        .trompeta {
            background-color: #079b91;
        }

        /* INFORMACIÓN */
        .informacion {
            height: 182px;
            padding: 17px 10px;
        }

        .informacion h3 {
            font-size: 16px;
            margin-bottom: 9px;
        }

        .informacion p {
            font-size: 11px;
            color: #444;
            margin-bottom: 27px;
        }

        .precio {
            color: #009688;
            font-size: 15px;
            font-weight: bold;
            margin-bottom: 11px;
        }

        /* BOTÓN */
        .btn {
            display: inline-block;
            background-color: #008f83;
            color: white;
            border: none;
            border-radius: 4px;
            padding: 8px 18px;
            font-size: 11px;
            font-weight: bold;
            cursor: pointer;
        }

        .btn:hover {
            background-color: #00766d;
        }

        /* RESPONSIVE */
        @media (max-width: 850px) {
            .galeria {
                width: 95%;
            }
        }

        @media (max-width: 600px) {
            .galeria {
                grid-template-columns: 1fr;
                width: 90%;
            }
        }
    </style>
</head>

<body>

    <header>
        <h1>🎵 GALERÍA DE INSTRUMENTOS MUSICALES</h1>
        <p>Encuentra instrumentos musicales para ti</p>
    </header>

    <main class="galeria">

        <!-- GUITARRA -->
        <div class="instrumento">
            <div class="imagen guitarra">
                <h2>Guitarra</h2>
            </div>

            <div class="informacion">
                <h3>Guitarra Acústica</h3>
                <p>Guitarra ideal para principiantes y músicos.</p>

                <div class="precio">S/ 450.00</div>

                <button class="btn">Comprar</button>
            </div>
        </div>

        <!-- PIANO -->
        <div class="instrumento">
            <div class="imagen piano">
                <h2>Piano</h2>
            </div>

            <div class="informacion">
                <h3>Piano Digital</h3>
                <p>Piano digital con excelente calidad de sonido.</p>

                <div class="precio">S/ 1,800.00</div>

                <button class="btn">Comprar</button>
            </div>
        </div>

        <!-- BATERÍA -->
        <div class="instrumento">
            <div class="imagen bateria">
                <h2>Batería</h2>
            </div>

            <div class="informacion">
                <h3>Batería Musical</h3>
                <p>Batería completa para practicar y tocar.</p>

                <div class="precio">S/ 2,200.00</div>

                <button class="btn">Comprar</button>
            </div>
        </div>

        <!-- VIOLÍN -->
        <div class="instrumento">
            <div class="imagen violin">
                <h2>Violín</h2>
            </div>

            <div class="informacion">
                <h3>Violín Clásico</h3>
                <p>Violín de madera con sonido cálido y claro.</p>

                <div class="precio">S/ 650.00</div>

                <button class="btn">Comprar</button>
            </div>
        </div>

        <!-- SAXOFÓN -->
        <div class="instrumento">
            <div class="imagen saxofon">
                <h2>Saxofón</h2>
            </div>

            <div class="informacion">
                <h3>Saxofón Alto</h3>
                <p>Saxofón ideal para músicos principiantes.</p>

                <div class="precio">S/ 1,500.00</div>

                <button class="btn">Comprar</button>
            </div>
        </div>

        <!-- TROMPETA -->
        <div class="instrumento">
            <div class="imagen trompeta">
                <h2>Trompeta</h2>
            </div>

            <div class="informacion">
                <h3>Trompeta Profesional</h3>
                <p>Trompeta de excelente sonido y acabado.</p>

                <div class="precio">S/ 900.00</div>

                <button class="btn">Comprar</button>
            </div>
        </div>

    </main>

</body>
</html>
