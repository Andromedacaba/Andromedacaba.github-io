<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Empresa de Seguridad">
    <title>Empresa de Seguridad</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        /* Encabezado con dos colores (mitad rojo, mitad negro) y flexbox para alinear imagen y texto */
        header {
            background: linear-gradient(to right, red 50%, black 50%);
            color: white;
            padding: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        header img {
            width: 80px; /* Tamaño de la imagen */
            height: auto; /* Mantener la proporción de la imagen */
            margin-right: 20px; /* Espacio entre la imagen y el texto */
        }
        nav {
            background-color: #555;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: RED;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        .hero {
            background-color: BLACK;
            color: RED;
            padding: 100px 20px;
            text-align: center;
        }
        .hero h1 {
            margin: 0;
            font-size: 2.5rem;
        }
         .services {
            background-color: red; /* Fondo rojo */
            color: black; /* Letras negras */
            padding: 40px 20px;
            text-align: center;
        }
        .services h2 {
            font-size: 2rem;
            margin-bottom: 20px;
        }
        .service-item {
            margin-bottom: 20px;
        }
        footer {
            background-color: RED;
            color: black;
            text-align: center;
            padding: 20px;
        }
        .contact {
	background-color: black; /* Fondo rojo */
           color: red; /* Letras negras */
           padding: 40px 20px;
           text-align: center;
        }
        form input, form textarea {
            display: block;
            width: 80%;
            margin: 10px auto;
            padding: 10px;
            font-size: 1rem;
        }
        form button {
            padding: 10px 20px;
            background-color: RED;
            color: white;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <!-- Encabezado con imagen a la izquierda de la palabra Empresa -->
    <header>
        <img src="Logos.jpeg" alt="Logo de la empresa"> <!-- Imagen del logo -->
        <h1>Empresa de Seguridad Andromeda</h1>
    </header>

    <!-- Menú de navegación -->
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#servicios">Servicios</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <!-- Sección principal (Hero Section) -->
    <section class="hero" id="inicio">
        <h1>Protegemos lo que más importa</h1>
        <p>Soluciones integrales en seguridad para:</p>
	<p>HOGARES.</p>
	<p>NEGOCIOS.</p>
	<p>EMPRESAS.</p>
    </section>

    <!-- Sección de Servicios -->
    <section class="services" id="servicios">
        <h2>Nuestros Servicios</h2>
        <div class="service-item">
            <h3>Seguridad Física</h3>
            <p>Guardias de seguridad altamente capacitados para la protección de su empresa o residencia.</p>
        </div>
        <div class="service-item">
            <h3>Monitoreo de Cámaras</h3>
            <p>Control y vigilancia 24/7 con equipos de última tecnología.</p>
        </div>
        <div class="service-item">
            <h3>Instalación de Alarmas</h3>
            <p>Alarmas y sistemas de seguridad personalizables para cada necesidad.</p>
        </div>
    </section>

    <!-- Sección de Contacto -->
    <section class="contact" id="contacto">
        <h2>Contáctanos</h2>
        <form action="mailto:tuemail@empresa.com" method="post" enctype="text/plain">
            <input type="text" name="nombre" placeholder="Nombre" required>
            <input type="email" name="email" placeholder="Correo electrónico" required>
            <textarea name="mensaje" placeholder="Tu mensaje" rows="5" required></textarea>
            <button type="submit">Enviar Mensaje</button>
        </form>
    </section>

    <!-- Pie de página -->
    <footer>
        <p>&copy; 2024 Empresa de Seguridad Andromeda | Todos los derechos reservados</p>
    </footer>

</body>
</html>