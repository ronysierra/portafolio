<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Rony Sierra</title>
  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css?family=Roboto:400,700&display=swap" rel="stylesheet">
  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
  <!-- Custom CSS -->
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      padding-top: 80px;    /* Altura del header */
      padding-bottom: 100px; /* Ajusta este valor para que el contenido no quede oculto */
      margin: 0;
    }
    header {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      z-index: 1000;
      background: #343a40;
	  padding: 0.5rem 0; 
      color: white;
      padding: 1rem 0;
	  animation: fadeInHeader 0.8s ease-in-out;
    }
	    /* Animación de fade in para el header */
    @keyframes fadeInHeader {
      from {
        opacity: 0;
        transform: translateY(-20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    /* Transición en los enlaces del header */
    header nav a {
      color: white;
      margin-right: 1rem;
      transition: color 0.3s ease;
    }
    header nav a:hover {
      color: #ffd700;  /* Color al pasar el mouse */
    }
    .hero {
      position: relative;
      background: #222;
      height: 20vh;
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
      text-align: center;
      overflow: hidden;
    }
    /* Contenedor para la animación de partículas */
    #particles-js {
      position: absolute;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      z-index: 1;
    }
    /* Contenido del hero (texto) sobre la animación */
    .hero-content {
      position: relative;
      z-index: 2;
    }
    footer {
      position: fixed;
      bottom: 0;
      left: 0;
      width: 100%;
      background: #343a40;
      color: white;
      padding: 1rem 0;
      text-align: center;
      z-index: 1000;
    }
    .btn-custom {
      background-color: #343a40;
      color: #fff;
      transition: background-color 0.3s ease;
    }
    .btn-custom:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>
  <!-- Header -->

  <header>
    <div class="container d-flex align-items-center justify-content-between">
      <div class="header-logo d-flex align-items-center">
		  <img src="assets/images/foto_Rony.jpg" alt="Foto de [Tu Nombre]" class="img-fluid rounded-circle" style="width: 60px; height: 60px; margin-right: 10px;">
		  <h2>Rony Miguel Sierra Rozo</h2>
		</div>
		<!-- Menú de navegación -->
		<nav>
		  <a href="index.html">Inicio</a>
		  <a href="about.html">Sobre mí</a>
		  <a href="cv.html">CV</a>
		  <a href="projects.html">Proyectos</a>
		</nav>
	  </div>
	</header>
  <!-- Hero Section -->
  <section class="hero">
  <div id="particles-js"></div>
  <div class="hero-content container">
      <h1>Bienvenido a mi portafolio de proyectos</h1>
      <p>Descubre mis proyectos y experiencias en ciencia de datos.</p>
    </div>
  </section>

  <!-- Contenido Principal (puedes agregar más secciones aquí) -->
  <main class="container my-5">
    <h2 class="mb-4">Sobre mí</h2>
    <p>Soy una persona altamente motivada y orientada a resultados, con más de 7 años de experiencia en analítica de datos y 3 años en administración de redes LAN. Actualmente estoy cursando un MBA, lo que me permite fortalecer mi visión estratégica y habilidades de liderazgo en la gestión de proyectos y equipos. Me destaco por mi enfoque propositivo, mi capacidad para identificar problemas y diseñar soluciones efectivas, y mi compromiso con la excelencia. Mi experiencia incluye la gestión de bases de datos, análisis y visualización de datos en herramientas como Excel, Access y Power BI, así como habilidades avanzadas en SQL, Python y R. He sido reconocido por mi contribución en operaciones clave del Grupo América Móvil en diversos países de LATAM y actualmente el equipo comercial de agentes de la zona Risaralda. Como Jefe Regional de Agentes, lidero un equipo comercial de más de 120 personas, promoviendo una cultura basada en la confianza, el empoderamiento y la colaboración. He implementado una metodología de ejecución enfocada en alinear esfuerzos hacia metas claras y alcanzables para maximizar los resultados del equipo. Mi misión es potenciar a las organizaciones mediante el uso inteligente de los datos, generando información estratégica que impulsa decisiones clave y el éxito empresarial.</p>
    
  </main>

  <!-- Footer -->
<footer class="container-fluid bg-dark text-white p-3 text-center">
  <div class="container">
      <p>© 2025 Rony Miguel Sierra Rozo - <a href="https://github.com/ronysierra" target="_blank" class="text-light"><i class="fab fa-github"></i> GitHub    <p>
      <i class="fas fa-phone"></i> +57 318 3892223 |
      <i class="fas fa-envelope"></i> rony.sierra@outlook.com |
      <i class="fab fa-linkedin"></i> <a href="https://www.linkedin.com/in/ronysierra/" target="_blank" class="text-white">LinkedIn</a> |
      <i class="fab fa-github"></i> <a href="https://github.com/ronysierra/" target="_blank" class="text-white">GitHub</a>
    </p>
  </div>
  <script src="https://kit.fontawesome.com/a076d05399.js"></script>
</footer>

  <!-- Bootstrap JS (opcional, para interactividad) -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
