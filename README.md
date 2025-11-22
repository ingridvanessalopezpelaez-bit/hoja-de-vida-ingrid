<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Hoja de Vida — Ingrid Vanessa López Pelaez</title>

  <!-- Google font -->
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&family=Libre+Franklin:wght@300;400;600&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg-left: #f6eef0; /* rosa suave */
      --text: #222;
      --muted: #666;
      --accent: #2f2f2f;
      --container-max: 1000px;
      --gap: 28px;
    }

    *{box-sizing:border-box}
    html,body{height:100%; margin:0; font-family: 'Libre Franklin', system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; color:var(--text); background:#fff;}
    a{color:inherit; text-decoration:none}

    .wrap{
      max-width:var(--container-max);
      margin:24px auto;
      background:#fff;
      display:grid;
      grid-template-columns: 320px 1fr;
      gap:var(--gap);
      padding:28px;
      border-radius:8px;
      box-shadow: 0 6px 22px rgba(0,0,0,0.06);
    }

    /* LEFT SIDEBAR */
    .sidebar{
      background:var(--bg-left);
      padding:28px;
      border-radius:8px;
      display:flex;
      flex-direction:column;
      gap:20px;
      align-items:center;
    }

    .photo{
      width:160px; height:160px;
      border-radius:50%;
      overflow:hidden;
      border:8px solid #fff;
      box-shadow:0 4px 14px rgba(0,0,0,0.06);
      background:#ddd;
    }

    .photo img{width:100%; height:100%; object-fit:cover; display:block}

    .profile-text{
      font-size:15px;
      line-height:1.45;
      color:var(--muted);
      text-align:center;
    }

    .contact{
      width:100%;
    }

    .contact h3{
      margin:0 0 8px 0;
      font-size:15px;
      letter-spacing:0.6px;
      color:var(--accent);
      display:flex;
      align-items:center;
      gap:10px;
      font-weight:700;
    }

    .contact p{margin:6px 0; font-size:14px; color:var(--muted)}

    .education{
      width:100%;
    }

    .section-title{
      display:flex; align-items:center; gap:10px;
      font-weight:700; color:var(--accent);
      margin-bottom:8px;
      font-size:15px;
    }

    .edu-item{font-size:14px; color:var(--text); margin-bottom:12px}

    /* RIGHT CONTENT */
    .content{
      padding:6px 6px 6px 14px;
    }

    header .name{
      font-family: 'Montserrat', sans-serif;
      font-weight:700;
      font-size:28px;
      letter-spacing:1px;
      margin:0;
      color:var(--accent);
    }

    header .subtitle{
      font-size:13px;
      margin-top:6px;
      color:var(--muted);
      font-style:italic;
      letter-spacing:0.6px;
    }

    .experience{
      margin-top:18px;
    }

    .job{
      margin-bottom:12px;
    }

    .job h4{margin:0; font-size:16px; color:var(--accent); font-weight:600}
    .job .period{font-size:13px; color:var(--muted); margin-bottom:8px}
    .job ul{margin:0; padding-left:18px; color:var(--muted); font-size:14px}
    .job ul li{margin-bottom:6px}

    /* Courses list */
    .courses .course{margin-bottom:14px}
    .course strong{display:block; color:var(--accent); margin-bottom:4px}
    .course span{display:block; color:var(--muted); font-size:13px}

    hr.sep{border:0; height:1px; background:linear-gradient(90deg, rgba(0,0,0,0.06), rgba(0,0,0,0.02)); margin:18px 0}

    /* Responsive for small screens */
    @media (max-width:820px){
      .wrap{grid-template-columns: 1fr; padding:18px}
      .sidebar{flex-direction:row; gap:14px; align-items:flex-start}
      .photo{width:110px;height:110px; border-width:6px}
      .profile-text{flex:1; text-align:left}
    }

    @media (max-width:420px){
      .photo{width:90px;height:90px}
      header .name{font-size:22px}
    }
  </style>
</head>
<body>

  <main class="wrap" role="main">
    <!-- LEFT -->
    <aside class="sidebar" aria-label="Información personal">
      <div class="photo" aria-hidden="true">
        <!-- Reemplaza 'photo.jpg' por el nombre de tu archivo de foto -->
        <img src="photo.jpg" alt="Foto de Ingrid Vanessa López Pelaez">
      </div>

      <div class="profile-text">
        Soy una persona proactiva, organizada y responsable, con buenas relaciones interpersonales. Siempre tengo la mejor disposición para la realización de mis labores. Busco un puesto desafiante donde pueda continuar aprendiendo.
      </div>

      <div class="contact">
        <h3>CONTACTO</h3>
        <p><strong>Celular:</strong> 321 5403832</p>
        <p><strong>Correo:</strong> ingridvanessalopezpelaez@gmail.com</p>
        <p><strong>Dirección:</strong> Calle 114b #64c-98, Boyacá las Brisas - Medellín</p>
      </div>

      <div class="education">
        <div class="section-title">EDUCACIÓN</div>
        <div class="edu-item">
          <strong>Tecnología en Gestión Empresarial</strong>
          <div style="color:var(--muted); font-size:13px">SENA — Nov 2015 hasta Nov 2017</div>
        </div>
        <div class="edu-item">
          <strong>Tecnología en Desarrollo Multimedia y Web</strong>
          <div style="color:var(--muted); font-size:13px">SENA — Etapa lectiva</div>
        </div>
        <div class="edu-item">
          <strong>Bachiller Técnico Administrativo</strong>
          <div style="color:var(--muted); font-size:13px">I.E. Bartolomé Logoguerrero — 2008</div>
        </div>
      </div>

      <div class="education">
        <div class="section-title">CURSOS</div>
        <div style="font-size:13px;color:var(--muted)">
          Diplomado en Marketing Digital Virtual - Comfenalco (80 horas) — finalizado 9 de marzo de 2023<br>
          Diplomado en Mercadeo y Ventas Virtual - Comfenalco (80 horas) — finalizado 3 de mayo de 2022<br>
          Curso avanzado en hojas de cálculo — 80 horas — finalizado 8 de junio de 2020
        </div>
      </div>

    </aside>

    <!-- RIGHT -->
    <section class="content" aria-label="Experiencia laboral y habilidades">
      <header>
        <h1 class="name">INGRID VANESSA<br>LOPEZ PELAEZ</h1>
        <div class="subtitle">Tecnóloga en Gestión Empresarial · Tecnólogo en Desarrollo Multimedia y Web</div>
      </header>

      <hr class="sep">

      <section class="experience" aria-label="Experiencia laboral">
        <div class="section-title">EXPERIENCIA LABORAL</div>

        <div class="job">
          <h4>Auxiliar de Mercadeo — Auxiliar Digital</h4>
          <div class="period">Desde Nov. 16 - 2021 · Actualmente</div>
          <ul>
            <li>Creadora de contenido y planificación de publicaciones (Instagram, Facebook, TikTok, blogs).</li>
            <li>Auditoría de página web y manejo de Shopify.</li>
            <li>Movimiento de productos, elaboración de linesheets y códigos de descuento.</li>
            <li>Logística de eventos, inventarios y controles.</li>
            <li>Elaboración de informes de gestión y métricas.</li>
            <li>Edición de video y contenidos multimedia.</li>
            <li>Trabajo en equipo para cumplimiento de objetivos y gestión de tareas y plazos.</li>
          </ul>
        </div>

      </section>

      <hr class="sep">

      <section class="skills">
        <div class="section-title">HABILIDADES Y RESPONSABILIDADES</div>
        <ul style="padding-left:18px; color:var(--muted); font-size:14px;">
          <li>Planificación, publicación y difusión de contenidos originales y de calidad.</li>
          <li>Incremento de visibilidad de marca y gestión de comunidades.</li>
          <li>Definición de objetivos, métricas y planificación de estrategias.</li>
          <li>Unificación de mensajes públicos y tono de voz.</li>
          <li>Elaboración de calendarios de publicaciones en distintas plataformas.</li>
        </ul>
      </section>

      <hr class="sep">

      <section class="courses">
        <div class="section-title">CURSOS ADICIONALES</div>

        <div class="course">
          <strong>Diplomado en Marketing Digital — Comfenalco</strong>
          <span>Finalizado 9 marzo 2023 — Duración: 80 horas</span>
        </div>

        <div class="course">
          <strong>Diplomado en Mercadeo y Ventas — Comfenalco</strong>
          <span>Finalizado 3 mayo 2022 — Duración: 80 horas</span>
        </div>

        <div class="course">
          <strong>Herramientas avanzadas de hojas de cálculo</strong>
          <span>Finalizado 8 junio 2020 — Duración: 80 horas</span>
        </div>
      </section>

    </section>
  </main>

</body>
</html>
