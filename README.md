<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instrumentos Musicales</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #222;
        }

        /* ENCABEZADO */
        header {
            background-color: #303f9f;
            color: white;
            text-align: center;
            padding: 24px 20px;
        }

        header h1 {
            font-size: 22px;
            margin-bottom: 3px;
        }

        header p {
            font-size: 11px;
            font-weight: bold;
        }

        /* MENÚ */
        nav {
            background-color: #202d86;
            text-align: center;
            padding: 11px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-size: 11px;
            font-weight: bold;
            margin: 0 14px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* CONTENIDO PRINCIPAL */
        main {
            max-width: 800px;
            margin: 26px auto;
            padding: 0 15px;
        }

        .introduccion {
            background-color: white;
            padding: 20px;
            border-radius: 7px;
            box-shadow: 0 3px 8px rgba(0,0,0,0.12);
            margin-bottom: 22px;
        }

        .introduccion h2 {
            color: #263b9b;
            font-size: 17px;
            margin-bottom: 10px;
        }

        .introduccion p {
            font-size: 11px;
            line-height: 1.7;
        }

        /* TÍTULO */
        .titulo-servicios {
            text-align: center;
            color: #263b9b;
            font-size: 24px;
            margin: 20px 0;
        }

        /* TARJETAS */
        .instrumentos {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
        }

        .tarjeta {
            background-color: white;
            min-height: 188px;
            padding: 28px 18px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 4px 9px rgba(0,0,0,0.12);
        }

        .icono {
            font-size: 35px;
            margin-bottom: 12px;
        }

        .tarjeta h3 {
            color: #263b9b;
            font-size: 16px;
            margin-bottom: 10px;
        }

        .tarjeta p {
            font-size: 11px;
            line-height: 1.5;
        }

        /* PIE DE PÁGINA */
        footer {
            background-color: #202d86;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 26px;
            font-size: 11px;
            font-weight: bold;
        }

        /* DISEÑO RESPONSIVO */
        @media (max-width: 700px) {
            .instrumentos {
                grid-template-columns: 1fr;
            }

            main {
                max-width: 95%;
            }

            nav a {
                margin: 0 7px;
            }
        }
    </style>
</head>

<body>

    <!-- ENCABEZADO -->
    <header>
        <h1>Mundo Musical</h1>
        <p>Instrumentos musicales para todos</p>
    </header>

    <!-- MENÚ -->
    <nav>
        <a href="#">Inicio</a>
        <a href="#">Instrumentos</a>
        <a href="#">Nosotros</a>
        <a href="#">Contacto</a>
    </nav>

    <!-- CONTENIDO -->
    <main>

        <section class="introduccion">
            <h2>Instrumentos de ancho completo</h2>

            <p>
                Encuentra una gran variedad de instrumentos musicales para
                principiantes y profesionales. Contamos con instrumentos de
                cuerda, percusión y viento para todos los gustos.
            </p>
        </section>

        <h2 class="titulo-servicios">Nuestros Instrumentos</h2>

        <section class="instrumentos">

            <!-- TARJETA 1 -->
            <div class="tarjeta">
                <div class="icono">🎸</div>

                <h3>Guitarra</h3>

                <p>
                    Guitarras acústicas y eléctricas ideales para aprender,
                    practicar y disfrutar de la música.
                </p>
            </div>

            <!-- TARJETA 2 -->
            <div class="tarjeta">
                <div class="icono">🎹</div>

                <h3>Piano</h3>

                <p>
                    Pianos y teclados para interpretar melodías y desarrollar
                    tus habilidades musicales.
                </p>
            </div>

            <!-- TARJETA 3 -->
            <div class="tarjeta">
                <div class="icono">🥁</div>

                <h3>Batería</h3>

                <p>
                    Baterías y accesorios para crear ritmos, practicar y tocar
                    junto a tus canciones favoritas.
                </p>
            </div>

        </section>

    </main>

    <!-- PIE DE PÁGINA -->
    <footer>
        © 2026 Mundo Musical
    </footer>

</body>
</html>
