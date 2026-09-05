<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Acordes & Teclas - Tienda de Instrumentos Musicales</title>
    <!-- Bootstrap CSS CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;800&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
    
    <style>
        body {
            font-family: 'Open Sans', sans-serif;
            color: #333;
        }
        h1, h2, h3, h4, h5, h6 {
            font-family: 'Montserrat', sans-serif;
        }
        .hero-section {
            background: linear-gradient(rgba(0, 0, 0, 0.75), rgba(179, 0, 0, 0.6)), url('https://images.unsplash.com/photo-1511379938547-c1f69419868d?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80') center/cover;
            color: white;
            padding: 120px 0;
            text-align: center;
        }
        .section-title {
            font-weight: 800;
            text-transform: uppercase;
            margin-bottom: 50px;
            color: #1a1a1a;
        }
        .benefit-icon {
            font-size: 2.5rem;
            color: #b30000;
            margin-bottom: 20px;
        }
        .card-hover:hover {
            transform: translateY(-5px);
            transition: transform 0.3s ease;
        }
    </style>
</head>
<body>

    <!-- 1. HEADER & NAVBAR -->
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top shadow">
            <div class="container">
                <a class="navbar-brand fw-bold text-uppercase" href="#">Acordes<span class="text-danger">&</span>Teclas</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                    <ul class="navbar-nav align-items-center gap-3">
                        <li class="nav-item"><a class="nav-link" href="#beneficios">Beneficios</a></li>
                        <li class="nav-item"><a class="nav-link" href="#productos">Productos</a></li>
                        <li class="nav-item"><a class="nav-link" href="#testimonios">Testimonios</a></li>
                        <li class="nav-item"><a href="#comprar" class="btn btn-danger btn-sm text-uppercase fw-bold px-4 py-2">Comprar Ahora</a></li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <main style="margin-top: 56px;">

        <!-- 2. HERO / MASTHEAD & CTA -->
        <section class="hero-section">
            <div class="container">
                <span class="badge bg-danger text-uppercase px-3 py-2 mb-3 fs-6">Envíos a Todo el Perú</span>
                <h1 class="display-3 fw-bold mb-4">Despierta Al Músico Que Lleva Dentro</h1>
                <p class="lead mb-5 mx-auto" style="max-width: 700px;">Encuentra guitarras, teclados, baterías y accesorios de las mejores marcas mundiales con garantía oficial y calibración profesional.</p>
                <a href="#comprar" class="btn btn-danger btn-lg text-uppercase fw-bold px-5 py-3 shadow">
                    Comprar ahora
                </a>
            </div>
        </section>

        <!-- 3. BENEFICIOS -->
        <section id="beneficios" class="py-5 bg-light">
            <div class="container py-5">
                <h2 class="text-center section-title">¿Por qué comprar con nosotros?</h2>
                <div class="row g-4 text-center">
                    <div class="col-md-4">
                        <div class="p-4 bg-white rounded shadow-sm h-100 card-hover">
                            <div class="benefit-icon">🛠️</div>
                            <h4>Calibración Incluida</h4>
                            <p class="text-muted">Cada instrumento pasa por nuestro taller de luthería para asegurar la afinación y comodidad perfecta antes del envío.</p>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="p-4 bg-white rounded shadow-sm h-100 card-hover">
                            <div class="benefit-icon">📦</div>
                            <h4>Envíos Seguros</h4>
                            <p class="text-muted">Empaque de alta protección y cobertura total ante cualquier eventualidad durante el transporte a tu domicilio.</p>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="p-4 bg-white rounded shadow-sm h-100 card-hover">
                            <div class="benefit-icon">🎵</div>
                            <h4>Asesoría Experta</h4>
                            <p class="text-muted">Atención personalizada por músicos profesionales para ayudarte a elegir el equipo ideal para tus proyectos.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 4. SERVICIOS / PRODUCTOS -->
        <section id="productos" class="py-5">
            <div class="container py-5">
                <h2 class="text-center section-title">Instrumentos Destacados</h2>
                <div class="row g-4">
                    <div class="col-md-4">
                        <div class="card h-100 shadow-sm card-hover border-0">
                            <img src="images (1).jpg" class="card-img-top" alt="Guitarra Eléctrica">
                            <div class="card-body d-flex flex-column">
                                <span class="badge bg-danger text-white align-self-start mb-2">Más Vendido</span>
                                <h5 class="card-title fw-bold">Guitarra Eléctrica Stratocaster</h5>
                                <p class="card-text text-muted">Cuerpo de aliso, mástil de arce y cápsulas versátiles para cualquier género musical.</p>
                                <div class="mt-auto d-flex justify-content-between align-items-center pt-3 border-top">
                                    <span class="fs-4 fw-bold text-danger">S/ 1,450.00</span>
                                    <a href="#comprar" class="btn btn-outline-dark btn-sm text-uppercase fw-bold">Comprar</a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card h-100 shadow-sm card-hover border-0">
                            <img src="https://images.unsplash.com/photo-1552422535-c45813c61732?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" class="card-img-top" alt="Piano Digital">
                            <div class="card-body d-flex flex-column">
                                <span class="badge bg-dark text-white align-self-start mb-2">Alta Gama</span>
                                <h5 class="card-title fw-bold">Piano Digital 88 Notas</h5>
                                <p class="card-text text-muted">Acción de martillo graduado y sonido realista de piano de cola de concierto.</p>
                                <div class="mt-auto d-flex justify-content-between align-items-center pt-3 border-top">
                                    <span class="fs-4 fw-bold text-danger">S/ 2,890.00</span>
                                    <a href="#comprar" class="btn btn-outline-dark btn-sm text-uppercase fw-bold">Comprar</a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card h-100 shadow-sm card-hover border-0">
                            <img src="https://images.unsplash.com/photo-1519892300165-cb5542fb47c7?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" class="card-img-top" alt="Batería Acústica">
                            <div class="card-body d-flex flex-column">
                                <span class="badge bg-secondary text-white align-self-start mb-2">Profesional</span>
                                <h5 class="card-title fw-bold">Batería Acústica 5 Piezas</h5>
                                <p class="card-text text-muted">Kit completo con herrajes reforzados y excelente resonancia para directo o estudio.</p>
                                <div class="mt-auto d-flex justify-content-between align-items-center pt-3 border-top">
                                    <span class="fs-4 fw-bold text-danger">S/ 3,200.00</span>
                                    <a href="#comprar" class="btn btn-outline-dark btn-sm text-uppercase fw-bold">Comprar</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 5. TESTIMONIOS -->
        <section id="testimonios" class="py-5 bg-light">
            <div class="container py-5">
                <h2 class="text-center section-title">Lo que opinan nuestros clientes</h2>
                <div class="row g-4">
                    <div class="col-md-4">
                        <div class="p-4 bg-white rounded shadow-sm h-100">
                            <p class="text-muted fst-italic">"Compré mi guitarra eléctrica y llegó perfectamente calibrada. El nivel de atención y el empaque son impecables."</p>
                            <h6 class="fw-bold mb-0 text-dark">— Renzo Valdivia</h6>
                            <small class="text-danger">Guitarrista de Rock</small>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="p-4 bg-white rounded shadow-sm h-100">
                            <p class="text-muted fst-italic">"Excelente tienda en Lima. Me asesoraron muy bien para elegir mi primer piano digital y el envío fue rapidísimo."</p>
                            <h6 class="fw-bold mb-0 text-dark">— Valeria Ramos</h6>
                            <small class="text-danger">Pianista y Estudiante</small>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="p-4 bg-white rounded shadow-sm h-100">
                            <p class="text-muted fst-italic">"La calidad de los instrumentos y los precios justos hacen que siempre vuelva por accesorios y equipos de audio."</p>
                            <h6 class="fw-bold mb-0 text-dark">— Diego Huamán</h6>
                            <small class="text-danger">Productor Musical</small>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 6. LLAMADA A LA ACCIÓN -->
        <section id="comprar" class="py-5 bg-dark text-white text-center">
            <div class="container py-5">
                <div class="alert alert-danger d-inline-block px-4 py-2 mb-3 fw-bold text-uppercase" role="alert">
                    🔥 Descuento especial de temporada en tienda web
                </div>
                <h2 class="fw-bold mb-3">Eleva tu sonido al siguiente nivel</h2>
                <p class="lead mb-4 mx-auto" style="max-width: 600px;">Haz tu pedido hoy y aprovecha nuestros beneficios exclusivos en envíos y garantías.</p>
                <a href="#" class="btn btn-danger btn-lg text-uppercase fw-bold px-5 py-3 shadow">
                    Comprar ahora
                </a>
            </div>
        </section>

    </main>

    <!-- 7. FOOTER -->
    <footer class="bg-black text-secondary py-5 text-center">
        <div class="container">
            <h3 class="text-white fw-bold mb-2">Acordes & Teclas</h3>
            <p class="mb-4">La tienda de instrumentos musicales elegida por los músicos peruanos.</p>
            <div class="border-top border-secondary pt-4 text-muted small">
                <p>&copy; 2026 Acordes & Teclas. Todos los derechos reservados.</p>
            </div>
        </div>
    </footer>

    <!-- Bootstrap JS Bundle CDN -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
