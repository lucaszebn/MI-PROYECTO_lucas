# MI-PROYECTO_lucas
Lucas_Zeballos-Proyecto_de_ept
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Movimiento360 · Plataforma de actividad física</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<link rel="stylesheet" href="styles.css">

</head>
<body>

<!-- ============ HEADER ============ -->
<header>
  <div class="header-inner">
    <div class="logo">
      <i class="fas fa-running"></i> Movimiento<span>360</span>
    </div>
    <nav class="nav" id="mainNav">
      <a href="#page-home" data-nav="home" class="active">Inicio</a>
      <a href="#page-planes" data-nav="planes">Planes</a>
      <a href="#page-rutinas" data-nav="rutinas">Rutinas</a>
      <a href="#page-galeria" data-nav="galeria">Galería</a>
      <a href="#page-herramientas" data-nav="herramientas">Herramientas</a>
      <a href="#page-blog" data-nav="blog">Blog</a>
      <a href="#page-comunidad" data-nav="comunidad">Comunidad</a>
    </nav>
    <div class="header-actions">
      <button class="icon-btn" title="Cambiar tema"><i class="fas fa-moon" id="themeIcon"></i></button>
      <button class="icon-btn" title="Notificaciones"><i class="fas fa-bell"></i><span class="badge-dot"></span></button>
      <button class="btn btn-sm"><i class="fas fa-user"></i> Acceder</button>
      <button class="icon-btn mobile-toggle"><i class="fas fa-bars"></i></button>
    </div>
  </div>
</header>

<main>
<!-- ============ PÁGINA: HOME ============ -->
<section id="page-home" class="page active">
  <div class="hero">
    <div class="hero-bg"></div>
    <div class="container hero-grid">
      <div>
        <div class="hero-badge"><i class="fas fa-bolt"></i> Muévete a tu ritmo, donde estés</div>
        <h1>Actividad física <span class="highlight">desde casa o parque</span></h1>
        <p>Rutinas de movilidad, fuerza, resistencia y retos semanales. Elige según tu nivel, registra tus avances y mantené la motivación con nuestra comunidad.</p>
        <div class="hero-ctas">
          <a class="btn" href="#page-planes"><i class="fas fa-rocket"></i> Empezar ahora</a>
          <a class="btn btn-outline" href="#page-galeria"><i class="fas fa-images"></i> Ver galería</a>
        </div>
        <div class="hero-stats">
          <div class="hero-stat"><div class="num">2.5K+</div><div class="lbl">Rutinas completadas</div></div>
          <div class="hero-stat"><div class="num">98%</div><div class="lbl">Se sienten mejor</div></div>
          <div class="hero-stat"><div class="num">24/7</div><div class="lbl">Acceso total</div></div>
        </div>
      </div>
      <div class="hero-image">
        <img src="https://images.pexels.com/photos/4498606/pexels-photo-4498606.jpeg?auto=compress&cs=tinysrgb&w=1260" alt="Entrenamiento en casa">
        <div class="hero-float float-1"><i class="fas fa-check"></i> Rutina completada</div>
        <div class="hero-float float-2"><i class="fas fa-fire"></i> +120 kcal hoy</div>
        <div class="hero-float float-3"><i class="fas fa-trophy"></i> Racha: 7 días</div>
      </div>
    </div>
  </div>

  <section class="block">
    <div class="container">
      <div class="section-head">
        <span class="section-tag">¿Por qué Movimiento360?</span>
        <h2 class="section-title">Todo lo que necesitás para moverte</h2>
        <p class="section-sub">Una propuesta de actividad física responsable, flexible y pensada para sostener la constancia.</p>
      </div>
      <div class="grid grid-4">
        <div class="card"><div class="card-icon"><i class="fas fa-house"></i></div><h3>Desde casa</h3><p>Rutinas sin equipamiento o con elementos básicos que tenés en casa.</p></div>
        <div class="card"><div class="card-icon"><i class="fas fa-tree"></i></div><h3>Al aire libre</h3><p>Ejercicios para parques, plazas o cualquier espacio disponible.</p></div>
        <div class="card"><div class="card-icon"><i class="fas fa-chart-simple"></i></div><h3>Seguimiento</h3><p>Registrá tus avances, rachas y logros en tu panel personal.</p></div>
        <div class="card"><div class="card-icon"><i class="fas fa-users"></i></div><h3>Comunidad</h3><p>Compartí retos, motivación y experiencias con otras personas.</p></div>
      </div>
    </div>
  </section>

  <section class="block" style="padding-top:0">
    <div class="container">
      <div class="section-head">
        <span class="section-tag">Galería</span>
        <h2 class="section-title">Entrená donde estés</h2>
        <p class="section-sub">Movimiento, fuerza y energía en cada espacio.</p>
      </div>
      <div class="gallery">
        <div class="gallery-item"><img src="https://images.pexels.com/photos/4056723/pexels-photo-4056723.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Parque"><div class="gallery-overlay"><div><h4>Parque</h4><p>Entrenamiento funcional</p></div></div></div>
        <div class="gallery-item"><img src="https://images.pexels.com/photos/3822906/pexels-photo-3822906.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Fuerza"><div class="gallery-overlay"><div><h4>Fuerza</h4><p>Bandas y peso corporal</p></div></div></div>
        <div class="gallery-item"><img src="https://images.pexels.com/photos/4498482/pexels-photo-4498482.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Movilidad"><div class="gallery-overlay"><div><h4>Movilidad</h4><p>Estiramiento consciente</p></div></div></div>
        <div class="gallery-item"><img src="https://images.pexels.com/photos/4753928/pexels-photo-4753928.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Resistencia"><div class="gallery-overlay"><div><h4>Resistencia</h4><p>Circuito cardiovascular</p></div></div></div>
      </div>
    </div>
  </section>

  <section class="block" style="background:linear-gradient(180deg,transparent,#eef4f1)">
    <div class="container">
      <div class="section-head">
        <span class="section-tag">Testimonios</span>
        <h2 class="section-title">Historias que nos motivan</h2>
      </div>
      <div class="grid grid-3">
        <div class="testimonial"><div class="stars">★★★★★</div><p>"Empecé con movilidad y hoy sostengo 4 rutinas por semana. La app me ayudó a ser constante."</p><div class="testimonial-author"><div class="avatar">MG</div><div><div class="name">María González</div><div class="role">Usuaria desde 2024</div></div></div></div>
        <div class="testimonial"><div class="stars">★★★★★</div><p>"Los retos semanales son mi parte favorita. Me mantienen enfocado sin presionarme."</p><div class="testimonial-author"><div class="avatar">JP</div><div><div class="name">Juan Pérez</div><div class="role">Nivel intermedio</div></div></div></div>
        <div class="testimonial"><div class="stars">★★★★★</div><p>"Me encanta que sea responsable: no promete bajar de peso, solo acompañarte a moverte mejor."</p><div class="testimonial-author"><div class="avatar">LR</div><div><div class="name">Lucía Ramírez</div><div class="role">Principiante</div></div></div></div>
      </div>
    </div>
  </section>

  <div class="container">
    <div class="newsletter">
      <h2>Recibí tu reto semanal</h2>
      <p>Un correo por semana con la rutina, tips y motivación. Sin spam, prometido.</p>
      <form class="newsletter-form">
        <input type="email" placeholder="tu@email.com" required>
        <button type="submit" class="btn">Suscribirme</button>
      </form>
    </div>
  </div>
</section>

<!-- ============ PÁGINA: PLANES ============ -->
<section id="page-planes" class="page">
  <div class="container" style="padding-top:3rem">
    <div class="section-head">
      <span class="section-tag">Planes</span>
      <h2 class="section-title">Elegí cómo querés moverte</h2>
      <p class="section-sub">Todos los planes incluyen acceso a rutinas, retos y registro de avances. Cancelá cuando quieras.</p>
    </div>
    <div class="pricing">
      <div class="price-card">
        <h3>Gratuito</h3>
        <p class="desc">Para empezar y conocer la plataforma.</p>
        <div class="price">$0<span>/mes</span></div>
        <ul class="price-features">
          <li><i class="fas fa-check"></i> 3 rutinas básicas</li>
          <li><i class="fas fa-check"></i> Reto semanal</li>
          <li><i class="fas fa-check"></i> Registro de avances</li>
          <li class="no"><i class="fas fa-times"></i> Planes personalizados</li>
          <li class="no"><i class="fas fa-times"></i> Comunidad premium</li>
        </ul>
        <button class="btn btn-outline btn-block">Comenzar gratis</button>
      </div>
      <div class="price-card featured">
        <h3>Activo</h3>
        <p class="desc">Para quienes ya quieren sostener una rutina.</p>
        <div class="price">$9<span>/mes</span></div>
        <ul class="price-features">
          <li><i class="fas fa-check"></i> Todo lo del plan Gratuito</li>
          <li><i class="fas fa-check"></i> +50 rutinas completas</li>
          <li><i class="fas fa-check"></i> Planes por nivel</li>
          <li><i class="fas fa-check"></i> Estadísticas avanzadas</li>
          <li><i class="fas fa-check"></i> Comunidad premium</li>
        </ul>
        <button class="btn btn-block">Suscribirme</button>
      </div>
      <div class="price-card">
        <h3>Élite</h3>
        <p class="desc">Para entrenar con acompañamiento y metas claras.</p>
        <div class="price">$19<span>/mes</span></div>
        <ul class="price-features">
          <li><i class="fas fa-check"></i> Todo lo del plan Activo</li>
          <li><i class="fas fa-check"></i> Rutinas personalizadas</li>
          <li><i class="fas fa-check"></i> Seguimiento mensual</li>
          <li><i class="fas fa-check"></i> Videollamadas grupales</li>
          <li><i class="fas fa-check"></i> Acceso anticipado a retos</li>
        </ul>
        <button class="btn btn-outline btn-block">Elegir Élite</button>
      </div>
    </div>

    <div class="section-head mt-2" style="margin-top:4rem">
      <span class="section-tag">Comparativa</span>
      <h2 class="section-title">¿Qué incluye cada plan?</h2>
    </div>
    <div class="card" style="padding:0;overflow:hidden">
      <table style="width:100%;border-collapse:collapse;font-size:.9rem">
        <thead style="background:var(--primary);color:#fff">
          <tr><th style="padding:1rem;text-align:left">Característica</th><th>Gratuito</th><th>Activo</th><th>Élite</th></tr>
        </thead>
        <tbody>
          <tr style="border-bottom:1px solid var(--gray-light)"><td style="padding:1rem">Rutinas básicas</td><td class="text-center"><i class="fas fa-check" style="color:var(--success)"></i></td><td class="text-center"><i class="fas fa-check" style="color:var(--success)"></i></td><td class="text-center"><i class="fas fa-check" style="color:var(--success)"></i></td></tr>
          <tr style="border-bottom:1px solid var(--gray-light)"><td style="padding:1rem">Retos semanales</td><td class="text-center"><i class="fas fa-check" style="color:var(--success)"></i></td><td class="text-center"><i class="fas fa-check" style="color:var(--success)"></i></td><td class="text-center"><i class="fas fa-check" style="color:var(--success)"></i></td></tr>
          <tr style="border-bottom:1px solid var(--gray-light)"><td style="padding:1rem">Rutinas ilimitadas</td><td class="text-center"><i class="fas fa-times" style="color:var(--danger)"></i></td><td class="text-center"><i class="fas fa-check" style="color:var(--success)"></i></td><td class="text-center"><i class="fas fa-check" style="color:var(--success)"></i></td></tr>
          <tr style="border-bottom:1px solid var(--gray-light)"><td style="padding:1rem">Estadísticas avanzadas</td><td class="text-center"><i class="fas fa-times" style="color:var(--danger)"></i></td><td class="text-center"><i class="fas fa-check" style="color:var(--success)"></i></td><td class="text-center"><i class="fas fa-check" style="color:var(--success)"></i></td></tr>
          <tr style="border-bottom:1px solid var(--gray-light)"><td style="padding:1rem">Planes personalizados</td><td class="text-center"><i class="fas fa-times" style="color:var(--danger)"></i></td><td class="text-center"><i class="fas fa-times" style="color:var(--danger)"></i></td><td class="text-center"><i class="fas fa-check" style="color:var(--success)"></i></td></tr>
          <tr><td style="padding:1rem">Videollamadas grupales</td><td class="text-center"><i class="fas fa-times" style="color:var(--danger)"></i></td><td class="text-center"><i class="fas fa-times" style="color:var(--danger)"></i></td><td class="text-center"><i class="fas fa-check" style="color:var(--success)"></i></td></tr>
        </tbody>
      </table>
    </div>

    <div class="section-head" style="margin-top:4rem">
      <span class="section-tag">Preguntas frecuentes</span>
      <h2 class="section-title">Resolvemos tus dudas</h2>
    </div>
    <div style="max-width:780px;margin:0 auto">
      <div class="faq-item"><div class="faq-q">¿Necesito equipamiento? <i class="fas fa-chevron-down"></i></div><div class="faq-a"><p>No. La mayoría de las rutinas usan peso corporal. Algunas opcionales sugieren bandas elásticas o una esterilla, pero siempre hay alternativas sin equipamiento.</p></div></div>
      <div class="faq-item"><div class="faq-q">¿Sirve para bajar de peso? <i class="fas fa-chevron-down"></i></div><div class="faq-a"><p>Esta es una propuesta de actividad física, no una garantía de pérdida de peso. Los resultados varían según cada persona y dependen de múltiples factores. Priorizá tu salud y consultá a un profesional.</p></div></div>
      <div class="faq-item"><div class="faq-q">¿Puedo cancelar cuando quiera? <i class="fas fa-chevron-down"></i></div><div class="faq-a"><p>Sí. Los planes pagos se cancelan en cualquier momento y seguís teniendo acceso hasta el final del período abonado.</p></div></div>
      <div class="faq-item"><div class="faq-q">¿Qué pasa si soy principiante? <i class="fas fa-chevron-down"></i></div><div class="faq-a"><p>Hay rutinas específicas para principiantes. Empezá progresivamente, respetá tus límites personales y consultá a un profesional si tenés dudas o condiciones preexistentes.</p></div></div>
      <div class="faq-item"><div class="faq-q">¿Funciona sin internet? <i class="fas fa-chevron-down"></i></div><div class="faq-a"><p>Podés descargar las rutinas en la app móvil para usarlas sin conexión. El registro se sincroniza cuando vuelvas a estar online.</p></div></div>
    </div>
  </div>
</section>

<!-- ============ PÁGINA: RUTINAS ============ -->
<section id="page-rutinas" class="page">
  <div class="container" style="padding-top:3rem">
    <div class="section-head">
      <span class="section-tag">Rutinas</span>
      <h2 class="section-title">Elegí por nivel y objetivo</h2>
      <p class="section-sub">Filtrá las rutinas según tu nivel, el lugar y el tipo de entrenamiento.</p>
    </div>

    <div class="filter-bar">
      <button class="chip active">Todas</button>
      <button class="chip">Principiante</button>
      <button class="chip">Intermedio</button>
      <button class="chip">Avanzado</button>
      <button class="chip">Casa</button>
      <button class="chip">Parque</button>
    </div>

    <div class="grid grid-3" id="routinesGrid">
      <div class="card routine" data-level="principiante" data-place="casa"><div class="card-icon"><i class="fas fa-person-walking"></i></div><h3>Movilidad matutina</h3><p>15 min · Estiramientos suaves para despertar el cuerpo y mejorar el rango de movimiento.</p><div class="routine-footer"><span class="tag">Principiante</span><button class="btn btn-sm"><i class="fas fa-play"></i> Iniciar</button></div></div>
      <div class="card routine" data-level="principiante" data-place="casa"><div class="card-icon"><i class="fas fa-heart-pulse"></i></div><h3>Cardio suave en casa</h3><p>20 min · Circuito de bajo impacto para activar la circulación sin saltos.</p><div class="routine-footer"><span class="tag">Principiante</span><button class="btn btn-sm"><i class="fas fa-play"></i> Iniciar</button></div></div>
      <div class="card routine" data-level="intermedio" data-place="casa"><div class="card-icon"><i class="fas fa-dumbbell"></i></div><h3>Fuerza con peso corporal</h3><p>25 min · Sentadillas, flexiones y planchas para tonificar todo el cuerpo.</p><div class="routine-footer"><span class="tag">Intermedio</span><button class="btn btn-sm"><i class="fas fa-play"></i> Iniciar</button></div></div>
      <div class="card routine" data-level="intermedio" data-place="parque"><div class="card-icon"><i class="fas fa-tree"></i></div><h3>Circuito en parque</h3><p>30 min · Usá bancos y barandas para un entrenamiento funcional completo.</p><div class="routine-footer"><span class="tag">Intermedio</span><button class="btn btn-sm"><i class="fas fa-play"></i> Iniciar</button></div></div>
      <div class="card routine" data-level="avanzado" data-place="casa"><div class="card-icon"><i class="fas fa-fire"></i></div><h3>HIIT avanzado</h3><p>20 min · Intervalos de alta intensidad para maximizar resistencia y energía.</p><div class="routine-footer"><span class="tag">Avanzado</span><button class="btn btn-sm"><i class="fas fa-play"></i> Iniciar</button></div></div>
      <div class="card routine" data-level="avanzado" data-place="parque"><div class="card-icon"><i class="fas fa-mountain"></i></div><h3>Resistencia outdoor</h3><p>40 min · Trote + estaciones de fuerza para llevar tu resistencia al siguiente nivel.</p><div class="routine-footer"><span class="tag">Avanzado</span><button class="btn btn-sm"><i class="fas fa-play"></i> Iniciar</button></div></div>
    </div>

    <div class="track-section mt-2" style="margin-top:3.5rem">
      <div class="container">
        <div class="track-grid">
          <div>
            <span class="section-tag">Reto de la semana</span>
            <h2 class="track-title">Completá 5 días de movimiento</h2>
            <p class="track-desc">Sumate al reto semanal y registrá cada día completado. La constancia es tu mejor aliada.</p>
            <div class="track-stats">
              <div class="stat-box"><div class="num">5</div><div class="lbl">Días objetivo</div></div>
              <div class="stat-box"><div class="num" id="retoProgress">0</div><div class="lbl">Días completados</div></div>
            </div>
            <div class="progress-bar" style="margin-top:1.5rem;background:rgba(255,255,255,.2)">
              <div class="progress-fill" id="retoBar" style="background:var(--accent)"></div>
            </div>
            <button class="btn btn-accent" style="margin-top:1.5rem"><i class="fas fa-plus"></i> Registrar día de hoy</button>
          </div>
          <div class="timer-card">
            <div class="timer-label">Temporizador de entrenamiento</div>
            <div class="timer-display" id="timerDisplay">00:00</div>
            <div class="timer-controls mt-2">
              <button class="btn btn-sm" id="timerBtn"><i class="fas fa-play"></i> Iniciar</button>
              <button class="btn btn-sm btn-outline"><i class="fas fa-rotate-left"></i> Reiniciar</button>
            </div>
            <div class="timer-presets">
              <button class="chip">1 min</button>
              <button class="chip">5 min</button>
              <button class="chip">10 min</button>
              <button class="chip">20 min</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ============ PÁGINA: GALERÍA ============ -->
<section id="page-galeria" class="page">
  <div class="container" style="padding-top:3rem">
    <div class="section-head">
      <span class="section-tag">Galería</span>
      <h2 class="section-title">Momentos de movimiento</h2>
      <p class="section-sub">Imágenes reales de entrenamiento en casa, parque y espacios disponibles.</p>
    </div>
    <div class="gallery">
      <div class="gallery-item"><img src="https://images.pexels.com/photos/4056723/pexels-photo-4056723.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Parque"><div class="gallery-overlay"><div><h4>Parque</h4><p>Entrenamiento funcional</p></div></div></div>
      <div class="gallery-item"><img src="https://images.pexels.com/photos/3822906/pexels-photo-3822906.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Fuerza"><div class="gallery-overlay"><div><h4>Fuerza</h4><p>Bandas elásticas</p></div></div></div>
      <div class="gallery-item"><img src="https://images.pexels.com/photos/4498482/pexels-photo-4498482.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Movilidad"><div class="gallery-overlay"><div><h4>Movilidad</h4><p>Estiramiento en casa</p></div></div></div>
      <div class="gallery-item"><img src="https://images.pexels.com/photos/4753928/pexels-photo-4753928.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Resistencia"><div class="gallery-overlay"><div><h4>Resistencia</h4><p>Cardio al aire libre</p></div></div></div>
      <div class="gallery-item"><img src="https://images.pexels.com/photos/2294361/pexels-photo-2294361.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Yoga"><div class="gallery-overlay"><div><h4>Yoga</h4><p>Equilibrio y respiración</p></div></div></div>
      <div class="gallery-item"><img src="https://images.pexels.com/photos/4162487/pexels-photo-4162487.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Estiramiento"><div class="gallery-overlay"><div><h4>Estiramiento</h4><p>Post-entreno</p></div></div></div>
      <div class="gallery-item"><img src="https://images.pexels.com/photos/4753933/pexels-photo-4753933.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Circuito"><div class="gallery-overlay"><div><h4>Circuito</h4><p>Fuerza y cardio</p></div></div></div>
      <div class="gallery-item"><img src="https://images.pexels.com/photos/3768916/pexels-photo-3768916.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Meditación"><div class="gallery-overlay"><div><h4>Calma</h4><p>Respiración consciente</p></div></div></div>
    </div>
  </div>
</section>

<!-- ============ PÁGINA: HERRAMIENTAS ============ -->
<section id="page-herramientas" class="page">
  <div class="container" style="padding-top:3rem">
    <div class="section-head">
      <span class="section-tag">Herramientas</span>
      <h2 class="section-title">Calculadoras y utilidades</h2>
      <p class="section-sub">Recursos para acompañar tu actividad física de forma responsable.</p>
    </div>

    <div class="grid grid-2">
      <div class="tool-card">
        <h3><i class="fas fa-calculator" style="color:var(--primary)"></i> Calculadora de IMC</h3>
        <p class="tool-desc">Una referencia orientativa. No reemplaza una evaluación profesional.</p>
        <div class="form-row">
          <div class="form-group"><label>Peso (kg)</label><input type="number" class="form-control" id="imcWeight" placeholder="70"></div>
          <div class="form-group"><label>Altura (cm)</label><input type="number" class="form-control" id="imcHeight" placeholder="170"></div>
        </div>
        <button class="btn btn-block"><i class="fas fa-equals"></i> Calcular IMC</button>
        <div class="imc-result" id="imcResult" style="display:none">
          <div class="imc-num" id="imcValue">0</div>
          <div class="imc-cat" id="imcCategory">—</div>
          <div class="imc-scale"><div style="background:#2563eb"></div><div style="background:#16a34a"></div><div style="background:#f59e0b"></div><div style="background:#dc2626"></div></div>
        </div>
      </div>

      <div class="tool-card">
        <h3><i class="fas fa-fire" style="color:var(--primary)"></i> Calorías estimadas</h3>
        <p class="tool-desc">Cálculo aproximado según actividad y duración. Valores orientativos.</p>
        <div class="form-group"><label>Tipo de actividad</label>
          <select class="form-control" id="calActivity">
            <option value="5">Movilidad / estiramiento</option>
            <option value="8" selected>Fuerza moderada</option>
            <option value="10">Cardio / HIIT</option>
            <option value="7">Caminata rápida</option>
          </select>
        </div>
        <div class="form-group"><label>Duración (minutos)</label><input type="number" class="form-control" id="calDuration" placeholder="30" value="30"></div>
        <div class="form-group"><label>Tu peso (kg)</label><input type="number" class="form-control" id="calWeight" placeholder="70" value="70"></div>
        <button class="btn btn-block"><i class="fas fa-fire"></i> Estimar calorías</button>
        <div class="imc-result" id="calResult" style="display:none">
          <div class="imc-num" id="calValue">0</div>
          <div class="imc-cat">kcal aproximadas</div>
        </div>
      </div>
    </div>

    <div class="section-head" style="margin-top:4rem">
      <span class="section-tag">Recomendaciones responsables</span>
      <h2 class="section-title">Entrená con seguridad</h2>
    </div>
    <div class="grid grid-4">
      <div class="card"><div class="card-icon"><i class="fas fa-chart-line"></i></div><h3>Progresión</h3><p>Empezá de a poco y aumentá la intensidad gradualmente.</p></div>
      <div class="card"><div class="card-icon"><i class="fas fa-hand-peace"></i></div><h3>Respetá tus límites</h3><p>Escuchá a tu cuerpo. El descanso también es parte del entrenamiento.</p></div>
      <div class="card"><div class="card-icon"><i class="fas fa-tint"></i></div><h3>Hidratación</h3><p>Bebé agua antes, durante y después de la actividad física.</p></div>
      <div class="card"><div class="card-icon"><i class="fas fa-user-md"></i></div><h3>Consulta profesional</h3><p>Ante dudas o condiciones preexistentes, consultá a un especialista.</p></div>
    </div>
    <p class="disclaimer mt-2">
      <i class="fas fa-circle-info" style="color:var(--primary)"></i> Esta propuesta de actividad física no garantiza la pérdida de peso. Los resultados varían según cada persona. Siempre priorizá tu salud y consultá a un profesional cuando sea necesario.
    </p>
  </div>
</section>

<!-- ============ PÁGINA: BLOG ============ -->
<section id="page-blog" class="page">
  <div class="container" style="padding-top:3rem">
    <div class="section-head">
      <span class="section-tag">Blog</span>
      <h2 class="section-title">Ideas, tips y motivación</h2>
      <p class="section-sub">Artículos breves para acompañar tu proceso.</p>
    </div>
    <div class="grid grid-3">
      <div class="blog-card"><img src="https://images.pexels.com/photos/4498482/pexels-photo-4498482.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Movilidad"><div class="blog-body"><div class="blog-meta">Movilidad · 5 min</div><h3>3 estiramientos para empezar el día</h3><p>Rutina corta para activar el cuerpo al despertar sin forzar articulaciones.</p></div></div>
      <div class="blog-card"><img src="https://images.pexels.com/photos/4753928/pexels-photo-4753928.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Constancia"><div class="blog-body"><div class="blog-meta">Hábitos · 4 min</div><h3>Cómo sostener la constancia sin obsesionarte</h3><p>Estrategias simples para que el movimiento sea parte de tu rutina, no una carga.</p></div></div>
      <div class="blog-card"><img src="https://images.pexels.com/photos/3822906/pexels-photo-3822906.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Fuerza"><div class="blog-body"><div class="blog-meta">Fuerza · 6 min</div><h3>Fuerza en casa con peso corporal</h3><p>Ejercicios básicos y progresiones para tonificar sin equipamiento.</p></div></div>
      <div class="blog-card"><img src="https://images.pexels.com/photos/4056723/pexels-photo-4056723.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Parque"><div class="blog-body"><div class="blog-meta">Outdoor · 5 min</div><h3>Aprovechá el parque como gimnasio</h3><p>Ideas para entrenar al aire libre usando bancos, barandas y tu propio peso.</p></div></div>
      <div class="blog-card"><img src="https://images.pexels.com/photos/2294361/pexels-photo-2294361.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Respiración"><div class="blog-body"><div class="blog-meta">Bienestar · 3 min</div><h3>Respiración y movimiento: la dupla perfecta</h3><p>Cómo integrar la respiración consciente en tus entrenamientos.</p></div></div>
      <div class="blog-card"><img src="https://images.pexels.com/photos/4162487/pexels-photo-4162487.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Descanso"><div class="blog-body"><div class="blog-meta">Recuperación · 4 min</div><h3>El descanso también entrena</h3><p>Por qué los días de recuperación son clave para progresar sin lesionarte.</p></div></div>
    </div>
  </div>
</section>

<!-- ============ PÁGINA: COMUNIDAD ============ -->
<section id="page-comunidad" class="page">
  <div class="container" style="padding-top:3rem">
    <div class="section-head">
      <span class="section-tag">Comunidad</span>
      <h2 class="section-title">Movete con otras personas</h2>
      <p class="section-sub">Compartí logros, dudas y motivación en un espacio respetuoso.</p>
    </div>

    <div class="grid grid-2">
      <div class="card">
        <h3><i class="fas fa-comments" style="color:var(--primary)"></i> Foro de la comunidad</h3>
        <p>Espacio para compartir experiencias y apoyarse mutuamente.</p>
        <div class="forum-list">
          <div class="forum-post">
            <div class="forum-head"><div class="avatar avatar-sm">MG</div><div><strong>María G.</strong><span class="forum-time">Hace 2 horas</span></div></div>
            <p>¿Alguien probó el reto de 5 días? Voy por el tercero y me está costando pero sigo 💪</p>
          </div>
          <div class="forum-post">
            <div class="forum-head"><div class="avatar avatar-sm">JP</div><div><strong>Juan P.</strong><span class="forum-time">Hace 5 horas</span></div></div>
            <p>Terminé el circuito de parque. ¡Recomendado! Los bancos sirven para mil ejercicios.</p>
          </div>
          <div class="forum-post">
            <div class="forum-head"><div class="avatar avatar-sm">LR</div><div><strong>Lucía R.</strong><span class="forum-time">Ayer</span></div></div>
            <p>Empecé con movilidad matutina. 15 min y ya me siento más suelta. ¡Gracias!</p>
          </div>
        </div>
      </div>

      <div class="card">
        <h3><i class="fas fa-trophy" style="color:var(--primary)"></i> Rankings de la semana</h3>
        <p>Las personas más constantes de los últimos 7 días.</p>
        <div class="ranking-list">
          <div class="ranking-item"><div class="rank-pos gold">1</div><div class="avatar avatar-sm">SR</div><div class="rank-info"><strong>Sofía R.</strong><span>7 días · 320 min</span></div><i class="fas fa-crown" style="color:var(--accent)"></i></div>
          <div class="ranking-item"><div class="rank-pos silver">2</div><div class="avatar avatar-sm">MG</div><div class="rank-info"><strong>María G.</strong><span>6 días · 280 min</span></div></div>
          <div class="ranking-item"><div class="rank-pos bronze">3</div><div class="avatar avatar-sm">JP</div><div class="rank-info"><strong>Juan P.</strong><span>5 días · 240 min</span></div></div>
        </div>
        <button class="btn btn-block mt-2"><i class="fas fa-user-plus"></i> Unirme a la comunidad</button>
      </div>
    </div>

    <div class="section-head" style="margin-top:4rem">
      <span class="section-tag">Próximos eventos</span>
      <h2 class="section-title">Entrenamientos en vivo</h2>
    </div>
    <div class="grid grid-3">
      <div class="card"><div class="card-icon"><i class="fas fa-video"></i></div><h3>Clase de movilidad</h3><p>Martes 20:00 · Online · 30 min</p><span class="tag">Gratuito</span></div>
      <div class="card"><div class="card-icon"><i class="fas fa-dumbbell"></i></div><h3>Fuerza en casa</h3><p>Jueves 19:00 · Online · 45 min</p><span class="tag">Plan Activo</span></div>
      <div class="card"><div class="card-icon"><i class="fas fa-tree"></i></div><h3>Circuito en parque</h3><p>Sábado 09:00 · Presencial · 60 min</p><span class="tag">Plan Élite</span></div>
    </div>
  </div>
</section>
</main>

<!-- ============ FOOTER ============ -->
<footer>
  <div class="container">
    <div class="footer-grid">
      <div>
        <div class="footer-brand"><i class="fas fa-running"></i> Movimiento360</div>
        <p class="footer-desc">Actividad física responsable desde casa, parque o cualquier espacio disponible. Movimiento, constancia y motivación.</p>
        <div class="footer-social">
          <a href="#" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
          <a href="#" aria-label="YouTube"><i class="fab fa-youtube"></i></a>
          <a href="#" aria-label="TikTok"><i class="fab fa-tiktok"></i></a>
          <a href="#" aria-label="WhatsApp"><i class="fab fa-whatsapp"></i></a>
        </div>
      </div>
      <div class="footer-col">
        <h4>Plataforma</h4>
        <a href="#page-planes">Planes</a>
        <a href="#page-rutinas">Rutinas</a>
        <a href="#page-herramientas">Herramientas</a>
        <a href="#page-galeria">Galería</a>
      </div>
      <div class="footer-col">
        <h4>Recursos</h4>
        <a href="#page-blog">Blog</a>
        <a href="#page-comunidad">Comunidad</a>
        <a href="#page-planes">Preguntas frecuentes</a>
        <a>Centro de ayuda</a>
      </div>
      <div class="footer-col">
        <h4>Legal</h4>
        <a>Términos y condiciones</a>
        <a>Política de privacidad</a>
        <a>Cookies</a>
        <a>Contacto</a>
      </div>
    </div>
    <div class="footer-bottom">
      <i class="fas fa-heart" style="color:var(--accent)"></i> Muévete, respirá, disfrutá. Actividad física responsable para todos.<br>
      &copy; 2025 Movimiento360. Esta propuesta no garantiza pérdida de peso. Consultá a un profesional cuando sea necesario.
    </div>
  </div>
</footer>

<!-- ============ MODAL AUTH ============ -->
<div class="modal-overlay" id="authModal">
  <div class="modal">
    <button class="modal-close"><i class="fas fa-times"></i></button>
    <h2 id="authTitle">Bienvenido de nuevo</h2>
    <p class="sub" id="authSub">Ingresá para ver tus avances y rutinas guardadas.</p>
    <div class="auth-tabs">
      <button id="tabLogin" class="active">Iniciar sesión</button>
      <button id="tabRegister">Crear cuenta</button>
    </div>
    <form id="authForm">
      <div class="form-group" id="nameGroup" style="display:none">
        <label>Nombre completo</label>
        <input type="text" class="form-control" placeholder="Tu nombre">
      </div>
      <div class="form-group">
        <label>Correo electrónico</label>
        <input type="email" class="form-control" placeholder="tu@email.com" required>
      </div>
      <div class="form-group">
        <label>Contraseña</label>
        <input type="password" class="form-control" placeholder="••••••••" required>
      </div>
      <button type="submit" class="btn btn-block" id="authBtn"><i class="fas fa-sign-in-alt"></i> Iniciar sesión</button>
    </form>
    <p class="modal-foot">Al continuar aceptás nuestros términos y política de privacidad.</p>
  </div>
</div>

<!-- ============ MODAL NOTIFICACIONES ============ -->
<div class="modal-overlay" id="notifModal">
  <div class="modal">
    <button class="modal-close"><i class="fas fa-times"></i></button>
    <h2>Notificaciones</h2>
    <p class="sub">Tus novedades recientes.</p>
    <div class="notif-list">
      <div class="notif-item"><i class="fas fa-trophy" style="color:var(--accent)"></i><div><strong>¡Racha de 7 días!</strong><p>Seguí así, estás imparable.</p></div></div>
      <div class="notif-item"><i class="fas fa-calendar" style="color:var(--primary)"></i><div><strong>Nuevo reto semanal disponible</strong><p>Completá 5 días de movimiento.</p></div></div>
      <div class="notif-item"><i class="fas fa-users" style="color:var(--info)"></i><div><strong>María G. te sigue</strong><p>Ahora formás parte de su red.</p></div></div>
    </div>
  </div>
</div>

<!-- ============ TOAST ============ -->
<div class="toast" id="toast"><i class="fas fa-check-circle"></i> <span id="toastMsg">Listo</span></div>
</body>
</html>
