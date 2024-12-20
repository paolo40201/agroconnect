<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AgroConnect - IoT Solutions</title>
    <link rel="icon" href="imagenes/favicon.ico" type="image/x-icon">
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: url('https://img.freepik.com/fotos-premium/campo-agricultura-uruguay_489856-739.jpg?w=740') no-repeat center center/cover;
            background-attachment: fixed;
            color: #333;
            line-height: 1.6;
        }

        /* Header */
        header {
            background: rgba(7, 128, 27, 0.9);
            color: #fff;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header .logo {
            font-size: 1.8rem;
            font-weight: bold;
            display: flex;
            align-items: center;
        }

        header .logo img {
            height: 40px;
            margin-right: 10px;
        }

        header nav ul {
            list-style: none;
            display: flex;
        }

        header nav ul li {
            margin-left: 1.5rem;
        }

        header nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1rem;
        }

        header nav ul li a:hover {
            color: #1abc9c;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: #fff;
            text-shadow: 1px 1px 4px #000;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 1.5rem;
        }

        .hero button {
            padding: 0.8rem 2rem;
            border: none;
            background: #1abc9c;
            color: #fff;
            font-size: 1rem;
            cursor: pointer;
            border-radius: 5px;
        }

        .hero button:hover {
            background: #16a085;
        }

        /* About Section */
        .about {
            padding: 2rem;
            text-align: center;
            background: rgba(255, 255, 255, 0.9);
            margin: 2rem auto;
            max-width: 800px;
            border-radius: 8px;
        }

        .about h2 {
            font-size: 2.2rem;
            margin-bottom: 1rem;
            color: #050101;
        }

        .about p {
            font-size: 1.1rem;
            color: #000000;
        }

        /* Footer */
        footer {
            background: rgba(29, 116, 204, 0.9);
            color: #fff;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="logo">
            <img src="xampp/htdocs/mi_proyecto/imagenes/hoja.jpeg" alt="AgroConnect Logo">
            AgroConnect
        </div>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#about">Sobre Nosotros</a></li>
                <li><a href="servicios.html">Servicios</a></li></a></li>
                <li><a href="contacto.html">Contacto</a></li>
               
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Conectando la Agricultura con el Futuro</h1>
        <p>Soluciones IoT innovadoras para una agricultura eficiente y sostenible.</p>
    </section>

    <!-- About Section -->
    <section class="about" id="about">
        <h2>Sobre Nosotros</h2>
        <p>En AgroConnect, proporcionamos soluciones tecnológicas innovadoras que integran IoT y agricultura. Optimizamos procesos agrícolas mediante dispositivos inteligentes, mejorando la productividad y sostenibilidad.</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 AgroConnect | Todos los derechos reservados</p>
    </footer>

    <!-- JavaScript -->
    <script>
        function mostrarCorreo() {
            alert("Correo electrónico: agroconnect.uy@gmail.com");
        }
    </script>
   
    
 
</body>
</html>

