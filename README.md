<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Personal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1em 0;
            border-bottom: 3px solid #388E3C;
        }
        .container {
            width: 80%;
            margin: auto;
            background-color: #fff;
            padding: 2em;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .profile {
            border: 2px solid #4CAF50;
            border-radius: 50%;
            width: 150px;
            height: 150px;
            margin: 0 auto;
            background-color: #e0e0e0;
            background-image: url('profile-pic.jpg'); /* Asegúrate de reemplazar con una imagen válida */
            background-size: cover;
            background-position: center;
        }
        .section {
            margin: 20px 0;
            padding: 1em;
            background-color: #e7f7e7;
            border: 1px solid #4CAF50;
            border-radius: 8px;
        }
        .section h2 {
            color: #4CAF50;
        }
        .contact-info {
            text-align: left;
            max-width: 600px;
            margin: 0 auto;
            background-color: #e0f7fa;
            padding: 1em;
            border-radius: 8px;
        }
        footer {
            background-color: #4CAF50;
            color: white;
            padding: 1em 0;
            border-top: 3px solid #388E3C;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenido a mi página personal</h1>
    </header>
    <div class="container">
        <div class="profile"></div>
        <section class="section" id="about">
            <h2>Sobre mí</h2>
            <p>Hola, soy [Tu Nombre]. Soy un entusiasta del desarrollo web y me encanta crear páginas atractivas y funcionales. Mi objetivo es aprender y crecer en el campo del desarrollo web.</p>
        </section>
        <section class="section" id="projects">
            <h2>Proyectos</h2>
            <p>Aquí puedes ver algunos de mis proyectos recientes.</p>
            <!-- Agrega detalles de tus proyectos aquí -->
        </section>
        <section class="contact-info" id="contact">
            <h2>Contacto</h2>
            <p>Si deseas ponerte en contacto conmigo, puedes enviarme un correo a: <a href="mailto:tuemail@example.com">tuemail@example.com</a></p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Mi Página Personal</p>
    </footer>
</body>
</html>
