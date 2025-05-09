# Unchain-your-second-language
My website
/mi-web
  
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Clases Online</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Clases Online</h1>
    <nav>
      <a href="#basico">Básico</a>
      <a href="#intermedio">Intermedio</a>
      <a href="#avanzado">Avanzado</a>
    </nav>
  </header>

  <section id="basico">
    <h2>Clases Básicas</h2>
    <p>Aquí encontrarás material introductorio para comenzar desde cero.</p>
  </section>

  <section id="intermedio">
    <h2>Clases Intermedias</h2>
    <p>Contenidos más avanzados para seguir creciendo.</p>
  </section>

  <section id="avanzado">
    <h2>Clases Avanzadas</h2>
    <p>Retos y proyectos para dominar completamente el tema.</p>
  </section>

  <footer>
    <p>&copy; 2025 Clases Online. Todos los derechos reservados.</p>
  </footer>
</body>
</html>

body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background-color: #000;
  color: #00aaff;
}

header {
  background-color: #0a0a0a;
  padding: 1rem;
  text-align: center;
  border-bottom: 2px solid #00aaff;
}

header h1 {
  margin: 0;
  font-size: 2rem;
}

nav {
  margin-top: 1rem;
}

nav a {
  color: #00aaff;
  margin: 0 1rem;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

section {
  padding: 2rem;
  border-bottom: 1px solid #222;
}

h2 {
  color: #00aaff;
}

footer {
  text-align: center;
  padding: 1rem;
  background-color: #0a0a0a;
  font-size: 0.9rem;
}

