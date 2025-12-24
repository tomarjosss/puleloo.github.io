cabañas pulelo
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Cabañas Pulelo | Alojamiento Turístico</title>
    <meta name="description" content="Cabañas Pulelo - Alojamiento cómodo y equipado en un entorno natural único. Ideal para descanso y turismo.">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- ESTILOS -->
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            color: #333;
            line-height: 1.6;
        }

        header {
            background: url("img/portada.jpg") center/cover no-repeat;
            color: white;
            text-align: center;
            padding: 120px 20px;
        }

        header h1 {
            font-size: 48px;
            margin-bottom: 10px;
        }

        header p {
            font-size: 20px;
        }

        nav {
            background: #2f6b4f;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        section {
            padding: 60px 20px;
            max-width: 1100px;
            margin: auto;
        }

        h2 {
            text-align: center;
            margin-bottom: 30px;
            color: #2f6b4f;
        }

        .servicios, .cabanas {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }

        .box {
            border: 1px solid #ddd;
            padding: 20px;
            border-radius: 5px;
        }

        .box img {
            width: 100%;
            border-radius: 5px;
        }

        .testimonio {
            background: #f4f4f4;
            padding: 20px;
            margin-bottom: 15px;
            border-left: 5px solid #2f6b4f;
        }

        footer {
            background: #2f6b4f;
            color: white;
            text-align: center;
            padding: 30px 20px;
        }

        footer a {
            color: white;
            text-decoration: none;
        }

        .contacto {
            text-align: center;
        }

        .contacto p {
            font-size: 18px;
        }
    </style>
</head>

<body>

<!-- MENÚ -->
<nav>
    <a href="#inicio">Inicio</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#cabanas">Cabañas</a>
    <a href="#servicios">Servicios</a>
    <a href="#contacto">Contacto</a>
</nav>

<!-- PORTADA -->
<header id="inicio">
    <h1>Cabañas Pulelo</h1>
    <p>Descanso, naturaleza y comodidad para tu estadía</p>
</header>

<!-- NOSOTROS -->
<section id="nosotros">
    <h2>Nosotros</h2>
    <p>
        En <strong>Cabañas Pulelo</strong> ofrecemos un espacio pensado para el descanso y la tranquilidad,
        rodeado de naturaleza y con todas las comodidades necesarias para que tu estadía sea
        una experiencia inolvidable.
    </p>
</section>

<!-- SERVICIOS -->
<section id="servicios">
    <h2>Nuestras Instalaciones</h2>
    <div class="servicios">
        <div class="box">✔ Cabañas totalmente equipadas</div>
        <div class="box">✔ Cocina completa</div>
        <div class="box">✔ Wi-Fi incluido</div>
        <div class="box">✔ Estacionamiento privado</div>
        <div class="box">✔ Ropa de cama y toallas</div>
        <div class="box">✔ Agua caliente</div>
    </div>
</section>

<!-- CABAÑAS -->
<section id="cabanas">
    <h2>Nuestras Cabañas</h2>

    <div class="cabanas">
        <div class="box">
            <img src="img/cabana1.jpg" alt="Cabaña Pulelo 1">
            <h3>Cabaña Pulelo 1</h3>
            <p>Capacidad: 4 personas</p>
            <ul>
                <li>2 dormitorios</li>
                <li>Cocina equipada</li>
                <li>TV</li>
                <li>Wi-Fi</li>
            </ul>
        </div>

        <div class="box">
            <img src="img/cabana2.jpg" alt="Cabaña Pulelo 2">
            <h3>Cabaña Pulelo 2</h3>
            <p>Capacidad: 6 personas</p>
            <ul>
                <li>3 dormitorios</li>
                <li>Living comedor</li>
                <li>Baño privado</li>
                <li>Estacionamiento</li>
            </ul>
        </div>

        <div class="box">
            <img src="img/cabana3.jpg" alt="Cabaña Pulelo 3">
            <h3>Cabaña Pulelo 3</h3>
            <p>Capacidad: 4 personas</p>
            <ul>
                <li>2 dormitorios</li>
                <li>Cocina completa</li>
                <li>Wi-Fi</li>
                <li>Calefacción</li>
            </ul>
        </div>
    </div>
</section>

<!-- TESTIMONIOS -->
<section>
    <h2>Testimonios</h2>

    <div class="testimonio">
        “Excelente lugar para descansar, muy cómodo y limpio.”
    </div>

    <div class="testimonio">
        “Muy buena atención y ubicación, totalmente recomendable.”
    </div>
</section>

<!-- CONTACTO -->
<section id="contacto" class="contacto">
    <h2>Contacto</h2>
    <p>📍 Dirección: [Tu dirección aquí]</p>
    <p>📞 Teléfono / WhatsApp: +56 9 XXXXXXXX</p>
    <p>✉ Email: contacto@cabanaspulelo.cl</p>
</section>

<!-- PIE DE PÁGINA -->
<footer>
    <p>© 2025 Cabañas Pulelo | Todos los derechos reservados</p>
</footer>

</body>
</html>
