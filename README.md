<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FiestIA - Que tu Celebración sea Inolvidable</title>
  <style>
    /* Estilos generales */
    body {
      font-family: 'Helvetica Neue', Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f8f9fa; /* Fondo claro */
      color: #333; /* Texto oscuro */
      line-height: 1.6;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
      text-align: center;
    }

    h1 {
      font-size: 2.5rem;
      color: #2c3e50; /* Azul oscuro */
      margin-bottom: 20px;
    }

    h2 {
      font-size: 1.8rem;
      color: #34495e; /* Azul grisáceo */
      margin-bottom: 30px;
    }

    p {
      font-size: 1.1rem;
      margin-bottom: 30px;
      color: #555; /* Texto gris oscuro */
    }

    .cta-button {
      display: inline-block;
      padding: 15px 40px;
      font-size: 1.2rem;
      color: #fff; /* Texto blanco */
      background-color: #3498db; /* Azul brillante */
      border-radius: 5px;
      text-decoration: none;
      transition: background-color 0.3s ease;
      font-weight: bold;
    }

    .cta-button:hover {
      background-color: #2980b9; /* Azul más oscuro */
    }

    /* Sección de características */
    .features {
      display: flex;
      justify-content: space-around;
      margin-top: 60px;
      flex-wrap: wrap; /* Para que se ajuste en móviles */
    }

    .feature {
      flex: 1;
      padding: 20px;
      background-color: #fff; /* Fondo blanco */
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      margin: 10px;
      min-width: 250px; /* Ancho mínimo para evitar que se vean muy pequeños */
      max-width: 100%; /* Asegura que no exceda el ancho de la pantalla */
    }

    .feature h3 {
      font-size: 1.5rem;
      color: #3498db; /* Azul brillante */
      margin-bottom: 15px;
    }

    .feature p {
      font-size: 1rem;
      color: #666; /* Texto gris */
    }

    /* Formulario */
    #formulario {
      margin-top: 60px;
    }

    #formulario input[type="email"] {
      padding: 12px;
      width: 100%; /* Ocupa todo el ancho disponible */
      max-width: 400px; /* Limita el ancho máximo */
      border: 1px solid #ccc;
      border-radius: 5px;
      background-color: #fff;
      color: #333;
      font-size: 1rem;
      box-sizing: border-box; /* Evita que el padding afecte el ancho */
    }

    #formulario button {
      margin-top: 15px;
      width: 100%; /* Ocupa todo el ancho disponible */
      max-width: 400px; /* Limita el ancho máximo */
      padding: 12px;
      font-size: 1rem;
    }

    /* Pie de página */
    footer {
      margin-top: 80px;
      padding: 20px;
      background-color: #2c3e50; /* Azul oscuro */
      color: #fff; /* Texto blanco */
      text-align: center;
    }

    footer a {
      color: #3498db; /* Azul brillante */
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }

    /* Estilos responsivos */
    @media (max-width: 768px) {
      h1 {
        font-size: 2rem; /* Tamaño más pequeño para móviles */
      }

      h2 {
        font-size: 1.5rem;
      }

      .features {
        flex-direction: column; /* Apila las columnas en móviles */
        align-items: center; /* Centra las tarjetas */
      }

      .feature {
        margin: 10px 0; /* Reduce el margen en móviles */
        width: 90%; /* Ocupa casi todo el ancho en móviles */
        max-width: 100%; /* Elimina el límite de ancho */
      }

      #formulario input[type="email"] {
        width: 90%; /* Ajusta el ancho del campo de correo */
        max-width: 100%; /* Elimina el límite de ancho */
      }

      #formulario button {
        width: 90%; /* Botón de ancho completo en móviles */
        max-width: 100%; /* Elimina el límite de ancho */
      }
    }

    @media (max-width: 480px) {
      h1 {
        font-size: 1.8rem; /* Tamaño más pequeño para pantallas muy pequeñas */
      }

      h2 {
        font-size: 1.3rem;
      }

      p {
        font-size: 1rem; /* Texto más pequeño en móviles */
      }

      .container {
        padding: 10px; /* Reduce el padding en móviles */
      }

      .cta-button {
        width: 90%; /* Botón de ancho completo en móviles */
        max-width: 100%; /* Elimina el límite de ancho */
        padding: 12px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Encabezado -->
    <header>
      <h1>FiestIA</h1>
      <h2>Que tu Celebración sea Inolvidable</h2>
      <p>
        Organiza <strong>tu boda</strong>, <strong>evento corporativo</strong>, o <strong>celebración privada</strong> en un solo lugar. 
        Con tecnología de vanguardia y un enfoque personalizado, cumple todo lo que imaginaste.
      </p>
      <a href="#formulario" class="cta-button">Reserva tu Evento</a>
    </header>

    <!-- Sección de Beneficios -->
    <section class="features">
      <div class="feature">
        <h3>Eventos Corporativos</h3>
        <p>Impresiona a tus clientes y socios con eventos diseñados para el éxito.</p>
      </div>
      <div class="feature">
        <h3>Bodas Únicas</h3>
        <p>Creamos bodas personalizadas que reflejan tu estilo y personalidad.</p>
      </div>
      <div class="feature">
        <h3>Celebraciones Privadas</h3>
        <p>Tu fiesta privada con cada detalle cuidado al máximo.</p>
      </div>
    </section>

    <!-- Formulario de Captación -->
    <section id="formulario">
      <h2>¿Listo para tu próximo evento?</h2>
      <p>Déjanos tu correo y nos pondremos en contacto contigo.</p>
      <form action="https://formsubmit.co/tucorreo@example.com" method="POST">
        <input type="email" name="email" placeholder="Tu correo electrónico" required>
        <button type="submit" class="cta-button">Enviar</button>
      </form>
    </section>

    <!-- Pie de Página -->
    <footer>
      <p>© 2025 FiestIA. Todos los derechos reservados.</p>
      <p><a href="#">Política de privacidad</a> | <a href="#">Términos de uso</a></p>
    </footer>
  </div>
</body>
</html>
