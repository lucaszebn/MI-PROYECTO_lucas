# MI-PROYECTO_lucas
Lucas_Zeballos-Proyecto_de_ept
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Movimiento360 · Actividad física desde casa o parque</title>
  <!-- Google Fonts e iconos -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,400;14..32,600;14..32,700;14..32,800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    /* ----- RESET Y ESTILOS BASE ----- */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background-color: #f8fafc;
      color: #0b1a2e;
      line-height: 1.5;
      scroll-behavior: smooth;
    }

    img {
      max-width: 100%;
      display: block;
      border-radius: 1.5rem;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 1.5rem;
    }

    /* ----- VARIABLES DE COLOR ----- */
    :root {
      --primary: #1b4d3d;        /* verde bosque profundo */
      --primary-light: #2e7d5e;
      --accent: #e6b91e;         /* amarillo energético */
      --accent-soft: #fde68a;
      --neutral-dark: #0b1a2e;
      --neutral-light: #f1f5f9;
      --white: #ffffff;
      --gray: #475569;
      --shadow: 0 20px 30px -10px rgba(0, 0, 0, 0.1);
    }

    /* ----- HEADER / NAV ----- */
    header {
      background-color: var(--white);
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.03);
      position: sticky;
      top: 0;
      z-index: 50;
      backdrop-filter: blur(8px);
      background-color: rgba(255, 255, 255, 0.9);
    }

    .header-flex {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 0.8rem 1.5rem;
      max-width: 1200px;
      margin: 0 auto;
    }

    .logo {
      display: flex;
      align-items: center;
      gap: 0.6rem;
      font-weight: 800;
      font-size: 1.6rem;
      letter-spacing: -0.02em;
      color: var(--primary);
    }

    .logo i {
      background: var(--primary);
      color: var(--white);
      padding: 0.5rem;
      border-radius: 50%;
      font-size: 1.2rem;
      width: 2.4rem;
      height: 2.4rem;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 8px 12px -6px rgba(27, 77, 61, 0.3);
    }

    .logo span {
      color: var(--neutral-dark);
      font-weight: 400;
    }

    .nav-links {
      display: flex;
      gap: 2rem;
      font-weight: 600;
    }

    .nav-links a {
      text-decoration: none;
      color: var(--neutral-dark);
      transition: color 0.2s;
      font-size: 1rem;
      position: relative;
    }

    .nav-links a::after {
      content: '';
      position: absolute;
      bottom: -4px;
      left: 0;
      width: 0;
      height: 2px;
      background: var(--accent);
      transition: width 0.2s;
    }

    .nav-links a:hover {
      color: var(--primary);
    }

    .nav-links a:hover::after {
      width: 100%;
    }

    .btn {
      display: inline-block;
      background: var(--primary);
      color: white;
      font-weight: 700;
      padding: 0.8rem 1.8rem;
      border-radius: 3rem;
      text-decoration: none;
      transition: background 0.2s, transform 0.1s;
      box-shadow: 0 10px 18px -8px rgba(27, 77, 61, 0.4);
      border: none;
      cursor: pointer;
      font-size: 0.95rem;
    }

    .btn:hover {
      background: var(--primary-light);
      transform: translateY(-2px);
    }

    .btn-outline {
      background: transparent;
      border: 2px solid var(--primary);
      color: var(--primary);
      box-shadow: none;
    }

    .btn-outline:hover {
      background: var(--primary);
      color: white;
    }

    /* ----- HERO SECTION ----- */
    .hero {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 2.5rem;
      align-items: center;
      padding: 3rem 1.5rem 4rem;
      max-width: 1200px;
      margin: 0 auto;
    }

    .hero-content h1 {
      font-size: 3.2rem;
      font-weight: 800;
      line-height: 1.2;
      letter-spacing: -0.03em;
      margin-bottom: 1.2rem;
      color: var(--neutral-dark);
    }

    .hero-content h1 span {
      color: var(--primary);
      border-bottom: 4px solid var(--accent);
    }

    .hero-content p {
      font-size: 1.2rem;
      color: var(--gray);
      margin-bottom: 2rem;
      max-width: 90%;
    }

    .hero-badge {
      display: inline-block;
      background: var(--accent-soft);
      color: #7a5800;
      font-weight: 700;
      padding: 0.4rem 1rem;
      border-radius: 3rem;
      font-size: 0.85rem;
      margin-bottom: 1.2rem;
      letter-spacing: 0.3px;
    }

    .hero-image img {
      width: 100%;
      height: 380px;
      object-fit: cover;
      box-shadow: var(--shadow);
      border-radius: 2rem;
    }

    /* ----- GALERÍA ----- */
    .gallery-section {
      padding: 4rem 0 5rem;
      background: linear-gradient(145deg, #ffffff 0%, #f4f9f7 100%);
    }

    .section-title {
      text-align: center;
      font-size: 2.4rem;
      font-weight: 800;
      letter-spacing: -0.02em;
      margin-bottom: 0.5rem;
      color: var(--neutral-dark);
    }

    .section-sub {
      text-align: center;
      color: var(--gray);
      margin-bottom: 3rem;
      font-size: 1.15rem;
      max-width: 700px;
      margin-left: auto;
      margin-right: auto;
    }

    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 1.5rem;
    }

    .gallery-item {
      border-radius: 1.8rem;
      overflow: hidden;
      box-shadow: 0 15px 25px -12px rgba(0, 0, 0, 0.2);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      background: white;
    }

    .gallery-item:hover {
      transform: translateY(-6px);
      box-shadow: 0 25px 30px -12px rgba(27, 77, 61, 0.3);
    }

    .gallery-item img {
      width: 100%;
      height: 240px;
      object-fit: cover;
      border-radius: 0;
      transition: transform 0.4s;
    }

    .gallery-item:hover img {
      transform: scale(1.03);
    }

    .gallery-caption {
      padding: 1rem 1rem 1.3rem;
      text-align: center;
      font-weight: 600;
      color: var(--primary);
      background: white;
    }

    .gallery-caption i {
      color: var(--accent);
      margin-right: 0.3rem;
    }

    /* ----- PLANES / TARJETAS ----- */
    .plans-section {
      padding: 5rem 0;
      background: white;
    }

    .cards-grid {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 1.8rem;
      margin-top: 1rem;
    }

    .card {
      background: #ffffff;
      border-radius: 2rem;
      padding: 2rem 1.5rem;
      box-shadow: 0 10px 25px -12px rgba(0, 0, 0, 0.08);
      border: 1px solid rgba(27, 77, 61, 0.08);
      transition: all 0.2s;
      display: flex;
      flex-direction: column;
      height: 100%;
    }

    .card:hover {
      border-color: var(--primary-light);
      box-shadow: 0 20px 30px -12px rgba(27, 77, 61, 0.2);
      transform: translateY(-4px);
    }

    .card-icon {
      font-size: 2.2rem;
      color: var(--primary);
      margin-bottom: 1.2rem;
      background: #e9f3ef;
      width: 3.8rem;
      height: 3.8rem;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 1.5rem;
    }

    .card h3 {
      font-size: 1.5rem;
      font-weight: 700;
      margin-bottom: 0.75rem;
      color: var(--neutral-dark);
    }

    .card p {
      color: var(--gray);
      font-size: 0.95rem;
      margin-bottom: 1.5rem;
      flex: 1;
    }

    .card .level-tag {
      display: inline-block;
      background: var(--accent-soft);
      color: #5e4200;
      font-weight: 700;
      font-size: 0.75rem;
      padding: 0.25rem 1rem;
      border-radius: 2rem;
      letter-spacing: 0.3px;
      align-self: flex-start;
    }

    /* ----- RETOS SEMANALES / REGISTRO ----- */
    .track-section {
      background: var(--primary);
      color: white;
      padding: 4rem 0;
      border-radius: 4rem 4rem 0 0;
      margin-top: 2rem;
    }

    .track-flex {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 2rem;
      flex-wrap: wrap;
    }

    .track-text h2 {
      font-size: 2.2rem;
      font-weight: 800;
      letter-spacing: -0.02em;
      margin-bottom: 1rem;
    }

    .track-text p {
      opacity: 0.9;
      max-width: 500px;
      margin-bottom: 1.8rem;
      font-size: 1.1rem;
    }

    .track-stats {
      display: flex;
      gap: 2rem;
      margin-top: 1.5rem;
    }

    .stat-item {
      background: rgba(255, 255, 255, 0.12);
      border-radius: 2rem;
      padding: 1.2rem 1.8rem;
      text-align: center;
      backdrop-filter: blur(6px);
    }

    .stat-item .number {
      font-size: 2rem;
      font-weight: 800;
      color: var(--accent);
    }

    .stat-item .label {
      font-size: 0.85rem;
      text-transform: uppercase;
      letter-spacing: 0.5px;
      opacity: 0.8;
    }

    .track-form {
      background: white;
      border-radius: 2.5rem;
      padding: 2.2rem;
      color: var(--neutral-dark);
      width: 100%;
      max-width: 400px;
      box-shadow: 0 25px 35px -10px rgba(0, 0, 0, 0.3);
    }

    .track-form h3 {
      font-size: 1.5rem;
      font-weight: 700;
      margin-bottom: 0.5rem;
    }

    .track-form p {
      color: var(--gray);
      font-size: 0.9rem;
      margin-bottom: 1.5rem;
    }

    .input-group {
      display: flex;
      flex-direction: column;
      gap: 0.9rem;
      margin-bottom: 1.8rem;
    }

    .input-group input, .input-group select {
      padding: 0.9rem 1.2rem;
      border-radius: 3rem;
      border: 1.5px solid #e2e8f0;
      font-family: 'Inter', sans-serif;
      font-size: 0.95rem;
      outline: none;
      transition: border 0.2s;
      background: #f9fcff;
    }

    .input-group input:focus, .input-group select:focus {
      border-color: var(--primary);
    }

    /* ----- RECOMENDACIONES ----- */
    .recommendations {
      padding: 4rem 0 5rem;
      background: var(--neutral-light);
    }

    .rec-grid {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 1.5rem;
      margin-top: 2.5rem;
    }

    .rec-item {
      background: white;
      border-radius: 2rem;
      padding: 1.8rem 1.5rem;
      text-align: center;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.03);
      transition: all 0.2s;
    }

    .rec-item:hover {
      background: var(--primary);
      color: white;
    }

    .rec-item:hover .rec-icon {
      color: var(--accent);
    }

    .rec-item:hover p {
      color: rgba(255, 255, 255, 0.9);
    }

    .rec-icon {
      font-size: 2.2rem;
      color: var(--primary);
      margin-bottom: 1rem;
      transition: color 0.2s;
    }

    .rec-item h4 {
      font-size: 1.2rem;
      font-weight: 700;
      margin-bottom: 0.6rem;
    }

    .rec-item p {
      color: var(--gray);
      font-size: 0.9rem;
      transition: color 0.2s;
    }

    /* ----- FOOTER ----- */
    footer {
      background: var(--neutral-dark);
      color: #cbd5e1;
      padding: 3rem 0;
      text-align: center;
    }

    footer .logo-footer {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 0.5rem;
      font-weight: 700;
      font-size: 1.4rem;
      margin-bottom: 1.5rem;
      color: white;
    }

    footer .logo-footer i {
      background: var(--accent);
      color: var(--neutral-dark);
      padding: 0.4rem;
      border-radius: 50%;
      width: 2.2rem;
      height: 2.2rem;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .footer-links {
      display: flex;
      justify-content: center;
      gap: 2.5rem;
      margin-bottom: 2rem;
      flex-wrap: wrap;
    }

    .footer-links a {
      color: #cbd5e1;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.2s;
    }

    .footer-links a:hover {
      color: var(--accent);
    }

    .footer-copy {
      font-size: 0.85rem;
      opacity: 0.7;
      border-top: 1px solid #1e2a3a;
      padding-top: 2rem;
      max-width: 800px;
      margin: 0 auto;
    }

    .footer-copy i {
      color: var(--accent);
      margin: 0 0.2rem;
    }

    /* ----- RESPONSIVE ----- */
    @media (max-width: 1000px) {
      .hero {
        grid-template-columns: 1fr;
        text-align: center;
        padding: 2rem 1.5rem 3rem;
      }

      .hero-content p {
        max-width: 100%;
        margin-left: auto;
        margin-right: auto;
      }

      .gallery-grid, .cards-grid, .rec-grid {
        grid-template-columns: repeat(2, 1fr);
      }

      .track-flex {
        flex-direction: column;
        text-align: center;
      }

      .track-text p {
        margin-left: auto;
        margin-right: auto;
      }

      .track-stats {
        justify-content: center;
      }

      .track-form {
        max-width: 100%;
      }

      .nav-links {
        display: none; /* simplificación para móvil, se puede mejorar */
      }
    }

    @media (max-width: 600px) {
      .gallery-grid, .cards-grid, .rec-grid {
        grid-template-columns: 1fr;
      }

      .hero-content h1 {
        font-size: 2.4rem;
      }

      .header-flex {
        flex-wrap: wrap;
        gap: 0.8rem;
        justify-content: center;
      }

      .track-stats {
        flex-direction: column;
        gap: 1rem;
        align-items: center;
      }

      .stat-item {
        width: 100%;
      }
    }

    /* ----- UTILIDADES ----- */
    .text-center {
      text-align: center;
    }

    .mt-2 {
      margin-top: 2rem;
    }
  </style>
</head>
<body>

  <!-- HEADER CON LOGO E ÍCONO -->
  <header>
    <div class="header-flex">
      <div class="logo">
        <i class="fas fa-running"></i>
        Movimiento<span>360</span>
      </div>
      <div class="nav-links">
        <a href="#planes">Planes</a>
        <a href="#galeria">Galería</a>
        <a href="#retos">Retos</a>
        <a href="#recomendaciones">Consejos</a>
      </div>
      <a href="#retos" class="btn">Registrar avance</a>
    </div>
  </header>

  <!-- HERO SECTION -->
  <section class="hero">
    <div class="hero-content">
      <div class="hero-badge">
        <i class="fas fa-bolt"></i> Muévete a tu ritmo
      </div>
      <h1>Actividad física <span>desde casa o parque</span></h1>
      <p>Rutinas de movilidad, fuerza, resistencia y retos semanales. Elige según tu nivel y registra tus avances con constancia y motivación.</p>
      <div style="display: flex; gap: 1rem; flex-wrap: wrap;">
        <a href="#planes" class="btn">Ver planes <i class="fas fa-arrow-right" style="margin-left: 0.5rem;"></i></a>
        <a href="#galeria" class="btn btn-outline">Galería</a>
      </div>
    </div>
    <div class="hero-image">
      <img src="https://images.pexels.com/photos/4498606/pexels-photo-4498606.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Persona entrenando en casa con esterilla">
    </div>
  </section>

  <!-- GALERÍA DE IMÁGENES DE ENTRENAMIENTO -->
  <section id="galeria" class="gallery-section">
    <div class="container">
      <h2 class="section-title">Entrena donde estés</h2>
      <p class="section-sub">Movimiento, fuerza y energía en cada espacio. Inspírate con nuestra galería.</p>
      <div class="gallery-grid">
        <div class="gallery-item">
          <img src="https://images.pexels.com/photos/4056723/pexels-photo-4056723.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Entrenamiento funcional en parque">
          <div class="gallery-caption"><i class="fas fa-tree"></i> Parque</div>
        </div>
        <div class="gallery-item">
          <img src="https://images.pexels.com/photos/3822906/pexels-photo-3822906.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Rutina de fuerza con bandas">
          <div class="gallery-caption"><i class="fas fa-dumbbell"></i> Fuerza</div>
        </div>
        <div class="gallery-item">
          <img src="https://images.pexels.com/photos/4498482/pexels-photo-4498482.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Movilidad y estiramiento en casa">
          <div class="gallery-caption"><i class="fas fa-person-walking"></i> Movilidad</div>
        </div>
        <div class="gallery-item">
          <img src="https://images.pexels.com/photos/4753928/pexels-photo-4753928.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Resistencia cardiovascular">
          <div class="gallery-caption"><i class="fas fa-heartbeat"></i> Resistencia</div>
        </div>
      </div>
    </div>
  </section>

  <!-- PLANES DE ACTIVIDAD FÍSICA -->
  <section id="planes" class="plans-section">
    <div class="container">
      <h2 class="section-title">Elige tu plan</h2>
      <p class="section-sub">Rutinas diseñadas para adaptarse a tu nivel. Empieza progresivamente y respeta tus límites.</p>
      <div class="cards-grid">
        <div class="card">
          <div class="card-icon"><i class="fas fa-seedling"></i></div>
          <h3>Movilidad</h3>
          <p>Mejora tu rango de movimiento y flexibilidad con secuencias suaves para hacer en casa.</p>
          <span class="level-tag">Principiante</span>
        </div>
        <div class="card">
          <div class="card-icon"><i class="fas fa-weight-hanging"></i></div>
          <h3>Fuerza</h3>
          <p>Ejercicios con peso corporal y bandas para tonificar y fortalecer músculos.</p>
          <span class="level-tag">Intermedio</span>
        </div>
        <div class="card">
          <div class="card-icon"><i class="fas fa-wind"></i></div>
          <h3>Resistencia</h3>
          <p>Circuitos cardiovasculares para aumentar tu energía y capacidad pulmonar.</p>
          <span class="level-tag">Todos los niveles</span>
        </div>
        <div class="card">
          <div class="card-icon"><i class="fas fa-calendar-check"></i></div>
          <h3>Reto semanal</h3>
          <p>Un desafío nuevo cada semana para mantener la constancia y la motivación.</p>
          <span class="level-tag">+500 activos</span>
        </div>
      </div>
    </div>
  </section>

  <!-- RETOS SEMANALES + REGISTRO DE AVANCES -->
  <section id="retos" class="track-section">
    <div class="container track-flex">
      <div class="track-text">
        <h2>Registra tus avances</h2>
        <p>Lleva el control de tus entrenamientos y celebra cada logro. La constancia es tu mejor aliada.</p>
        <div class="track-stats">
          <div class="stat-item">
            <div class="number">+2.5k</div>
            <div class="label">Rutinas completadas</div>
          </div>
          <div class="stat-item">
            <div class="number">98%</div>
            <div class="label">Se sienten mejor</div>
          </div>
        </div>
      </div>
      <div class="track-form">
        <h3><i class="fas fa-clipboard-list" style="color: var(--primary); margin-right: 0.5rem;"></i> Mi progreso</h3>
        <p>Completa y guarda tu actividad de hoy.</p>
        <div class="input-group">
          <select>
            <option selected disabled>Selecciona una actividad</option>
            <option>Movilidad - 15 min</option>
            <option>Fuerza - 20 min</option>
            <option>Resistencia - 30 min</option>
            <option>Reto semanal</option>
          </select>
          <input type="text" placeholder="Tu nombre">
          <input type="date">
        </div>
        <button class="btn" style="width: 100%; justify-content: center; display: flex; align-items: center; gap: 0.5rem;">
          <i class="fas fa-check-circle"></i> Guardar avance
        </button>
        <p style="font-size: 0.75rem; color: #94a3b8; margin-top: 1rem; margin-bottom: 0;">
          * Esta es una demostración. Los datos no se almacenan.
        </p>
      </div>
    </div>
  </section>

  <!-- RECOMENDACIONES GENERALES -->
  <section id="recomendaciones" class="recommendations">
    <div class="container">
      <h2 class="section-title">Recomendaciones responsables</h2>
      <p class="section-sub">Tu bienestar es lo primero. Sigue estas pautas para entrenar de forma segura.</p>
      <div class="rec-grid">
        <div class="rec-item">
          <div class="rec-icon"><i class="fas fa-chart-line"></i></div>
          <h4>Progresión</h4>
          <p>Empieza de a poco y aumenta la intensidad gradualmente.</p>
        </div>
        <div class="rec-item">
          <div class="rec-icon"><i class="fas fa-hand-peace"></i></div>
          <h4>Respeta tus límites</h4>
          <p>Escucha a tu cuerpo. El descanso también es entrenamiento.</p>
        </div>
        <div class="rec-item">
          <div class="rec-icon"><i class="fas fa-tint"></i></div>
          <h4>Hidratación</h4>
          <p>Bebe agua antes, durante y después de la actividad física.</p>
        </div>
        <div class="rec-item">
          <div class="rec-icon"><i class="fas fa-user-md"></i></div>
          <h4>Consulta profesional</h4>
          <p>Ante dudas o condiciones preexistentes, consulta a un especialista.</p>
        </div>
      </div>
      <p style="text-align: center; margin-top: 2.5rem; font-size: 0.9rem; color: #64748b; max-width: 800px; margin-left: auto; margin-right: auto;">
        <i class="fas fa-circle-info" style="color: var(--primary);"></i> 
        Esta propuesta de actividad física no garantiza la pérdida de peso. Los resultados varían según cada persona. 
        Siempre prioriza tu salud y consulta a un profesional cuando sea necesario.
      </p>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <div class="container">
      <div class="logo-footer">
        <i class="fas fa-running"></i> Movimiento360
      </div>
      <div class="footer-links">
        <a href="#planes">Planes</a>
        <a href="#galeria">Galería</a>
        <a href="#retos">Retos</a>
        <a href="#recomendaciones">Consejos</a>
      </div>
      <div class="footer-copy">
        <i class="fas fa-heart"></i> Muévete, respira, disfruta. Actividad física responsable para todos. <br>
        &copy; 2025 Movimiento360. Todos los derechos reservados.
      </div>
    </div>
  </footer>

</body>
</html>
