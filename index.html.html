<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>La Pesadilla del Conocimiento</title>
<style>
  :root {
    --bg: #070707;
    --panel: #101010;
    --panel2: #151515;
    --red: #e71932;
    --red-dark: #790b19;
    --text: #e7e7e7;
    --muted: #a4a4ad;
    --line: #64101c;
    --glow: 0 0 18px rgba(231,25,50,.12);
  }
  * { box-sizing: border-box; }
  html { scroll-behavior: smooth; }
  body {
    margin: 0; background: radial-gradient(ellipse at 70% 0%, #1b090c 0, var(--bg) 42%);
    color: var(--text); font: 15px/1.5 "Segoe UI", Arial, sans-serif;
  }
  button, input, textarea, select { font: inherit; }
  button { cursor: pointer; }
  .app { min-height: 100vh; display: grid; grid-template-columns: 245px minmax(0,1fr); }
  aside {
    background: #050505; border-right: 1px solid #292929; padding: 24px 16px;
    display: flex; flex-direction: column; gap: 22px; position: sticky; top: 0;
    height: 100vh; overflow-y: auto;
  }
  .brand { text-align: center; padding: 6px 0 18px; border-bottom: 1px solid #292929; }
  .eye { color: var(--red); font-size: 48px; line-height: 1; text-shadow: 0 0 16px #8b0018; }
  .brand h1 { font: 22px/1.15 Georgia, serif; letter-spacing: 1px; margin: 12px 0 8px; text-transform: uppercase; }
  .brand p { margin: 0; color: var(--muted); font-family: Georgia, serif; font-style: italic; font-size: 13px; }
  nav { display: grid; gap: 7px; }
  .nav-btn {
    width: 100%; border: 1px solid transparent; background: transparent; color: #c4c4ca;
    text-align: left; padding: 12px 13px; border-radius: 5px; display: flex; gap: 12px; align-items: center;
    transition: .2s;
  }
  .nav-btn .ico { width: 23px; color: #a5a5ad; font-size: 18px; text-align: center; }
  .nav-btn:hover, .nav-btn.active { color: #fff; background: linear-gradient(90deg, #31070e, #120608); border-color: var(--red-dark); }
  .nav-btn.active .ico, .nav-btn:hover .ico { color: var(--red); }
  .side-quote { border: 1px solid #343434; padding: 18px 14px; text-align: center; color: #b7b7c0; font: italic 15px/1.7 Georgia, serif; background: linear-gradient(#0b0b0b,#070707); }
  .side-bottom { margin-top: auto; color: var(--muted); font-size: 12px; }
  .online { color: #e8c62a; margin-top: 8px; }
  .dot { display: inline-block; width: 9px; height: 9px; border-radius: 50%; background: #f21d32; margin-right: 7px; box-shadow: 0 0 9px #f21d32; }
  main { min-width: 0; padding: 20px; }
  .hero {
    min-height: 210px; border: 1px solid #292020; position: relative; overflow: hidden; display: flex;
    align-items: center; padding: 30px; margin-bottom: 18px;
    background:
      linear-gradient(90deg, rgba(0,0,0,.94) 0%, rgba(0,0,0,.68) 52%, rgba(0,0,0,.25) 100%),
      radial-gradient(ellipse at 72% 35%, #555 0, #202020 12%, #090909 45%, #020202 80%);
  }
  .hero:before {
    content: "◉"; position: absolute; right: 18%; top: -75px; font-size: 280px; color: #222;
    text-shadow: 0 0 25px #000; opacity: .65; transform: rotate(-10deg); pointer-events: none;
  }
  .hero:after { content:""; position:absolute; inset:0; background:repeating-linear-gradient(0deg, transparent 0 4px, rgba(255,255,255,.018) 5px); pointer-events:none; }
  .hero-copy { max-width: 620px; position: relative; z-index: 1; }
  .eyebrow { color: var(--red); text-transform: uppercase; letter-spacing: 3px; font-size: 11px; }
  .hero h2 { font: clamp(28px,4vw,44px)/1.1 Georgia, serif; margin: 8px 0 12px; }
  .hero p { color: #c4c4c9; max-width: 510px; margin: 0 0 18px; }
  .bloodline { color: #ff3449; font: italic 17px Georgia, serif; letter-spacing: 2px; }
  .toprow { display: flex; align-items: center; justify-content: space-between; gap: 12px; margin: 0 0 16px; }
  .toprow h2 { margin: 0; font: 24px Georgia, serif; }
  .toprow small { color: var(--muted); }
  .clock { color: var(--red); font: 25px/1.2 "Courier New", monospace; letter-spacing: 2px; }
  .welcome-grid { display: grid; grid-template-columns: minmax(0,1fr) 220px; gap: 14px; margin-bottom: 14px; }
  .panel { border: 1px solid var(--line); background: linear-gradient(145deg, rgba(20,20,20,.96), rgba(5,5,5,.98)); padding: 17px; box-shadow: var(--glow); min-width: 0; }
  .panel h3 { margin: 0 0 12px; font: 19px Georgia, serif; border-left: 4px solid var(--red); padding-left: 10px; }
  .timer-panel { text-align: center; display: flex; flex-direction: column; justify-content: center; }
  .timer-panel p { color: #ff5363; font: italic 13px Georgia,serif; margin: 0 0 12px; }
  .timer-labels { display: flex; justify-content: space-around; color: var(--muted); font-size: 10px; margin-top: 8px; }
  .quick-grid { display: grid; grid-template-columns: repeat(4,minmax(0,1fr)); gap: 12px; margin-bottom: 16px; }
  .quick {
    border: 1px solid var(--red-dark); background: #0a090a; color: var(--text); padding: 15px 8px; border-radius: 4px;
    transition: .2s; text-align: center;
  }
  .quick:hover { border-color: var(--red); transform: translateY(-2px); box-shadow: 0 0 18px #3a0710; }
  .quick .ico { display: block; font-size: 25px; color: var(--red); margin-bottom: 5px; }
  .quick strong { font-weight: 500; }
  .content-grid { display: grid; grid-template-columns: minmax(0,1fr) minmax(0,1.1fr); gap: 14px; }
  .subject-list { display: grid; gap: 8px; }
  .subject {
    width: 100%; display: flex; align-items: center; gap: 12px; padding: 10px; color: var(--text);
    border: 1px solid #303035; background: #0b0b0d; text-align: left; border-radius: 5px; transition: .2s;
  }
  .subject:hover { border-color: var(--red-dark); background: #16090c; }
  .subject-icon { flex: 0 0 44px; height: 44px; display: grid; place-items: center; background: #050505; border: 1px solid #2b2b30; color: var(--red); font-size: 21px; }
  .subject span:nth-child(2) { flex: 1; }
  .subject small { display: block; color: var(--muted); margin-top: 2px; font-size: 12px; }
  .arrow { color: #999; font-size: 22px; }
  .right-stack { display: grid; align-content: start; gap: 14px; }
  .quote-panel { min-height: 140px; display: flex; gap: 14px; align-items: center; }
  .quote-mark { color: var(--red); font-size: 35px; line-height: 1; }
  .quote-text { font: italic 17px/1.6 Georgia,serif; }
  .quote-text small { display: block; margin-top: 7px; color: var(--muted); font: 12px "Segoe UI",sans-serif; }
  .task-list { display: grid; gap: 6px; }
  .task {
    display: flex; align-items: center; gap: 9px; border: 1px solid #303035; background: #080809;
    padding: 8px 10px; border-radius: 4px; font-size: 13px;
  }
  .task input { accent-color: var(--red); width: 16px; height: 16px; }
  .task span { flex: 1; }
  .task time { color: #aaa; font-size: 11px; }
  .task.done span { text-decoration: line-through; color: #777; }
  .add-task { display: flex; gap: 7px; margin-top: 10px; }
  input[type="text"], textarea, select {
    width: 100%; color: var(--text); background: #080808; border: 1px solid #383838; border-radius: 4px; padding: 10px;
  }
  input:focus, textarea:focus, select:focus { outline: 1px solid var(--red); border-color: var(--red); }
  .btn { background: #24070c; border: 1px solid var(--red-dark); color: #fff; padding: 9px 13px; border-radius: 4px; }
  .btn:hover { background: #4a0b16; border-color: var(--red); }
  .resources { display: grid; grid-template-columns: repeat(4,minmax(0,1fr)); gap: 8px; }
  .resource { padding: 12px 5px; background: #080808; border: 1px solid #2d2d32; border-radius: 4px; color: #c8c8cf; text-align: center; font-size: 12px; }
  .resource:hover { color: white; border-color: var(--red); }
  .resource b { display: block; color: var(--red); font-size: 20px; margin-bottom: 5px; }
  .feature { display: flex; gap: 18px; align-items: center; min-height: 120px; background: linear-gradient(90deg,#070707,#19070b); }
  .feature-art { font-size: 44px; color: #74101d; }
  .feature p { color: #ff334a; font: italic 16px/1.5 Georgia,serif; margin: 0 0 9px; }
  footer { text-align: center; color: #7f7f88; font-size: 12px; border-top: 1px solid #262626; margin-top: 20px; padding: 15px; }
  .view { display: none; }
  .view.active { display: block; animation: appear .25s ease; }
  @keyframes appear { from { opacity: 0; transform: translateY(5px); } to { opacity: 1; transform: translateY(0); } }
  .empty-note { color: var(--muted); font-size: 13px; }
  .notes-area { min-height: 190px; resize: vertical; }
  .setting-row { display:flex; justify-content:space-between; align-items:center; gap:14px; padding:12px 0; border-bottom:1px solid #292929; }
  .setting-row:last-child { border:0; }
  .setting-row p { margin: 2px 0 0; color: var(--muted); font-size: 12px; }
  body.lights-on { --bg:#171719; --panel:#242428; --panel2:#2b2b30; --text:#f1f1f1; }
  body.lights-on aside, body.lights-on .side-quote, body.lights-on .subject, body.lights-on .task, body.lights-on .resource { background-color:#1a1a1e; }
  .toast { position:fixed; bottom:20px; right:20px; max-width:300px; padding:12px 16px; background:#19070b; border:1px solid var(--red); color:#fff; z-index:10; box-shadow:0 0 22px #000; display:none; }
  .toast.show { display:block; animation:appear .2s ease; }
  @media(max-width:900px) {
    .app { grid-template-columns: 190px minmax(0,1fr); }
    aside { padding:18px 10px; }
    .brand h1 { font-size:18px; }
    .welcome-grid { grid-template-columns:1fr; }
    .timer-panel { min-height:125px; }
    .content-grid { grid-template-columns:1fr; }
  }
  @media(max-width:620px) {
    .app { display:block; }
    aside { height:auto; position:relative; padding:12px; border-right:0; border-bottom:1px solid #333; }
    .brand { display:flex; align-items:center; gap:12px; text-align:left; padding:0 0 12px; }
    .eye { font-size:34px; }
    .brand h1 { margin:0 0 4px; font-size:16px; }
    .brand p { font-size:12px; }
    nav { display:flex; overflow-x:auto; gap:5px; }
    .nav-btn { min-width:max-content; width:auto; padding:9px; font-size:13px; }
    .side-quote, .side-bottom { display:none; }
    main { padding:12px; }
    .hero { min-height:190px; padding:20px; }
    .hero:before { right:-30px; font-size:200px; }
    .quick-grid { grid-template-columns:repeat(2,minmax(0,1fr)); gap:8px; }
    .resources { grid-template-columns:repeat(2,minmax(0,1fr)); }
    .panel { padding:13px; }
    .toprow h2 { font-size:21px; }
  }
</style>
</head>
<body>
<div class="app">
  <aside>
    <div class="brand">
      <div class="eye" aria-hidden="true">◉</div>
      <div><h1>La Pesadilla<br>del Conocimiento</h1><p>No todo lo que aprendes te hará libre...</p></div>
    </div>
    <nav aria-label="Navegación principal">
      <button class="nav-btn active" data-view="inicio"><span class="ico">⌂</span> Inicio</button>
      <button class="nav-btn" data-view="materias"><span class="ico">▤</span> Materias</button>
      <button class="nav-btn" data-view="recursos"><span class="ico">▱</span> Recursos</button>
      <button class="nav-btn" data-view="calendario"><span class="ico">▦</span> Calendario</button>
      <button class="nav-btn" data-view="notas"><span class="ico">✎</span> Mis notas</button>
      <button class="nav-btn" data-view="configuracion"><span class="ico">⚙</span> Configuración</button>
    </nav>
    <div class="side-quote">“El conocimiento es una jaula de la que no todos pueden escapar.”</div>
    <div class="side-bottom">Usuario: Estudiante<br>Año escolar: 2026–2027<div class="online"><span class="dot"></span>Conectado</div></div>
  </aside>

  <main>
    <section class="hero">
      <div class="hero-copy">
        <div class="eyebrow">Archivo académico · Acceso restringido</div>
        <h2>El conocimiento también puede ser una pesadilla.</h2>
        <p>Tu refugio para organizar materias, recursos y tareas. Mantén el control de tus estudios… antes de que el semestre te controle a ti.</p>
        <div class="bloodline">Estudia. Aprende. Sobrevive.</div>
      </div>
    </section>

    <section id="inicio" class="view active">
      <div class="welcome-grid">
        <div class="panel">
          <div class="toprow"><h2>Bienvenido, estudiante</h2><small>Expediente #013</small></div>
          <p>Esta es tu página de apoyo escolar. Aquí encontrarás herramientas, recursos y todo lo que necesitas para mantenerte al día con tus clases.</p>
          <p class="bloodline">Tu próxima entrega está más cerca de lo que crees.</p>
        </div>
        <div class="panel timer-panel">
          <p>El tiempo también es parte del examen…</p><div class="clock" id="clock">00:00:00</div>
          <div class="timer-labels"><span>HORAS</span><span>MINUTOS</span><span>SEGUNDOS</span></div>
        </div>
      </div>
      <div class="quick-grid">
        <button class="quick" data-go="materias"><span class="ico">▤</span><strong>Ver materias</strong></button>
        <button class="quick" data-go="recursos"><span class="ico">▱</span><strong>Recursos</strong></button>
        <button class="quick" data-go="calendario"><span class="ico">▦</span><strong>Calendario</strong></button>
        <button class="quick" data-go="notas"><span class="ico">✎</span><strong>Mis notas</strong></button>
      </div>
      <div class="content-grid">
        <div>
          <div class="panel" style="margin-bottom:14px">
            <h3>Materias</h3>
            <div class="subject-list">
              <button class="subject" data-subject="Matemáticas"><span class="subject-icon">∑</span><span>Matemáticas<small>Funciones, ecuaciones y problemas</small></span><span class="arrow">›</span></button>
              <button class="subject" data-subject="Lengua y Literatura"><span class="subject-icon">▤</span><span>Lengua y Literatura<small>Lectura, redacción y Romanticismo</small></span><span class="arrow">›</span></button>
              <button class="subject" data-subject="Tecnología y Sociedad"><span class="subject-icon">⚙</span><span>Tecnología y Sociedad<small>Proyectos, pantallas y sociedad</small></span><span class="arrow">›</span></button>
              <button class="subject" data-subject="Formación Cívica y Ética"><span class="subject-icon">♧</span><span>Formación Cívica y Ética<small>Derechos, deberes y convivencia</small></span><span class="arrow">›</span></button>
              <button class="subject" data-subject="Inglés"><span class="subject-icon">⚑</span><span>Inglés<small>Grammar, vocabulary and practice</small></span><span class="arrow">›</span></button>
            </div>
          </div>
          <div class="panel">
            <h3>Accesos rápidos</h3>
            <div class="resources">
              <button class="resource" data-resource="Drive"><b>☁</b>Drive</button>
              <button class="resource" data-resource="Classroom"><b>⌂</b>Classroom</button>
              <button class="resource" data-resource="YouTube"><b>▶</b>YouTube</button>
              <button class="resource" data-resource="CONALEP"><b>↗</b>CONALEP</button>
            </div>
          </div>
        </div>
        <div class="right-stack">
          <div class="panel quote-panel"><div><h3>Frase del día</h3><div class="quote-text" id="quote">“A veces, lo más oscuro de la mente es lo que nos lleva a la luz.”<small>— Archivo anónimo</small></div><button class="btn" id="newQuote" style="margin-top:12px">Otra frase</button></div></div>
          <div class="panel">
            <h3>Tareas pendientes</h3>
            <div class="task-list" id="taskList">
              <label class="task"><input type="checkbox"><span>Entregar ficha de investigación (Deporte)</span><time>14/10</time></label>
              <label class="task"><input type="checkbox"><span>Resumen del Romanticismo</span><time>16/10</time></label>
              <label class="task"><input type="checkbox"><span>Infografía de discapacidad en el deporte</span><time>18/10</time></label>
              <label class="task"><input type="checkbox"><span>Proyecto final de Tecnología y Sociedad</span><time>25/10</time></label>
            </div>
            <div class="add-task"><input id="taskInput" type="text" placeholder="Añadir una tarea…"><button class="btn" id="addTask">Añadir</button></div>
          </div>
          <div class="panel feature"><div class="feature-art">▧</div><div><p>No es solo una página…<br>es tu refugio y tu prisión.</p><button class="btn" data-go="recursos">Explorar recursos →</button></div></div>
        </div>
      </div>
    </section>

    <section id="materias" class="view">
      <div class="toprow"><h2>Materias del semestre</h2><small>Selecciona una materia para ver sus detalles</small></div>
      <div class="content-grid">
        <div class="panel"><h3>Expediente académico</h3><div class="subject-list" id="allSubjects">
          <button class="subject" data-subject="Matemáticas"><span class="subject-icon">∑</span><span>Matemáticas<small>Funciones, álgebra y razonamiento</small></span><span class="arrow">›</span></button>
          <button class="subject" data-subject="Lengua y Literatura"><span class="subject-icon">▤</span><span>Lengua y Literatura<small>Comprensión y expresión escrita</small></span><span class="arrow">›</span></button>
          <button class="subject" data-subject="Tecnología y Sociedad"><span class="subject-icon">⚙</span><span>Tecnología y Sociedad<small>Tecnología, cultura y sociedad</small></span><span class="arrow">›</span></button>
          <button class="subject" data-subject="Formación Cívica y Ética"><span class="subject-icon">♧</span><span>Formación Cívica y Ética<small>Participación y ciudadanía</small></span><span class="arrow">›</span></button>
          <button class="subject" data-subject="Inglés"><span class="subject-icon">⚑</span><span>Inglés<small>Grammar and communication</small></span><span class="arrow">›</span></button>
        </div></div>
        <div class="panel" id="subjectDetails"><h3>Detalle de la materia</h3><p class="empty-note">Elige una materia para abrir su ficha.</p></div>
      </div>
    </section>

    <section id="recursos" class="view">
      <div class="toprow"><h2>Biblioteca de recursos</h2><small>Herramientas de estudio</small></div>
      <div class="content-grid">
        <div class="panel"><h3>Recursos de aprendizaje</h3><div class="subject-list">
          <button class="subject" data-resource="Guía de estudio"><span class="subject-icon">▤</span><span>Guía de estudio<small>Organiza los temas antes del examen</small></span><span class="arrow">›</span></button>
          <button class="subject" data-resource="Videos educativos"><span class="subject-icon">▶</span><span>Videos educativos<small>Apoyo visual para temas difíciles</small></span><span class="arrow">›</span></button>
          <button class="subject" data-resource="Diccionario"><span class="subject-icon">Aa</span><span>Diccionario<small>Consulta palabras y conceptos</small></span><span class="arrow">›</span></button>
          <button class="subject" data-resource="Apuntes personales"><span class="subject-icon">✎</span><span>Apuntes personales<small>Guarda ideas y recordatorios</small></span><span class="arrow">›</span></button>
        </div></div>
        <div class="panel"><h3>Consejo de supervivencia</h3><p>No intentes aprenderlo todo la noche anterior. Divide cada tema en bloques pequeños, toma descansos y repasa con tus propias palabras.</p><p class="bloodline">Una página a la vez. Un examen a la vez.</p><button class="btn" id="studyTip">Revelar otro consejo</button><p id="tipText" class="empty-note"></p></div>
      </div>
    </section>

    <section id="calendario" class="view">
      <div class="toprow"><h2>Calendario académico</h2><small>Fechas de ejemplo · Personalízalas</small></div>
      <div class="panel"><h3>Octubre: el mes de las entregas</h3>
        <div class="task-list">
          <label class="task"><input type="checkbox"><span>Ficha de investigación deportiva</span><time>14 oct.</time></label>
          <label class="task"><input type="checkbox"><span>Resumen del Romanticismo</span><time>16 oct.</time></label>
          <label class="task"><input type="checkbox"><span>Infografía de deporte adaptado</span><time>18 oct.</time></label>
          <label class="task"><input type="checkbox"><span>Proyecto final</span><time>25 oct.</time></label>
        </div>
        <p class="empty-note" style="margin-top:14px">Marca las casillas conforme completes tus pendientes. Las fechas son ejemplos y puedes cambiarlas en tu planificación.</p>
      </div>
    </section>

    <section id="notas" class="view">
      <div class="toprow"><h2>Mis notas</h2><small>Se guardan en este navegador</small></div>
      <div class="panel"><h3>Cuaderno secreto</h3><p>Escribe apuntes, ideas o recordatorios. Pulsa guardar para conservarlos en este dispositivo.</p>
        <textarea id="notesArea" class="notes-area" placeholder="Escribe aquí tus notas…"></textarea>
        <div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px"><button class="btn" id="saveNotes">Guardar notas</button><button class="btn" id="clearNotes">Borrar notas</button></div>
      </div>
    </section>

    <section id="configuracion" class="view">
      <div class="toprow"><h2>Configuración</h2><small>Ajusta tu espacio de estudio</small></div>
      <div class="panel"><h3>Preferencias</h3>
        <div class="setting-row"><div><strong>Modo de iluminación</strong><p>Cambia entre oscuridad total y un ambiente más claro.</p></div><button class="btn" id="lightToggle">Cambiar modo</button></div>
        <div class="setting-row"><div><strong>Efectos de sonido</strong><p>Esta página no reproduce sonidos automáticamente.</p></div><span class="empty-note">Desactivados</span></div>
        <div class="setting-row"><div><strong>Restablecer tareas</strong><p>Desmarca todas las tareas de la lista actual.</p></div><button class="btn" id="resetTasks">Restablecer</button></div>
        <div class="setting-row"><div><strong>Acerca del proyecto</strong><p>Una plantilla escolar gótica hecha con HTML, CSS y JavaScript, sin librerías externas.</p></div><span style="color:var(--red)">v1.0</span></div>
      </div>
    </section>
    <footer>La Pesadilla del Conocimiento · 2026 · Hecho para estudiantes, por un estudiante.</footer>
  </main>
</div>
<div class="toast" id="toast" role="status" aria-live="polite"></div>
<script>
  const navButtons = document.querySelectorAll('[data-view]');
  const views = document.querySelectorAll('.view');
  const toast = document.getElementById('toast');
  let toastTimer;
  function notify(message) {
    toast.textContent = message;
    toast.classList.add('show');
    clearTimeout(toastTimer);
    toastTimer = setTimeout(() => toast.classList.remove('show'), 2600);
  }
  function showView(id) {
    views.forEach(v => v.classList.toggle('active', v.id === id));
    navButtons.forEach(b => b.classList.toggle('active', b.dataset.view === id));
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }
  navButtons.forEach(b => b.addEventListener('click', () => showView(b.dataset.view)));
  document.querySelectorAll('[data-go]').forEach(b => b.addEventListener('click', () => showView(b.dataset.go)));

  function updateClock() {
    const d = new Date();
    document.getElementById('clock').textContent = [d.getHours(), d.getMinutes(), d.getSeconds()].map(n => String(n).padStart(2,'0')).join(':');
  }
  updateClock(); setInterval(updateClock, 1000);

  const subjectInfo = {
    'Matemáticas': 'Repasa procedimientos paso a paso. Anota las fórmulas, resuelve un ejemplo y después intenta uno sin mirar la solución.',
    'Lengua y Literatura': 'Organiza tus lecturas por autor, época, características y ejemplos. Para los resúmenes, escribe las ideas principales con tus palabras.',
    'Tecnología y Sociedad': 'Relaciona cada concepto tecnológico con un ejemplo real. Guarda fuentes y registra las ventajas, desventajas y el impacto social.',
    'Formación Cívica y Ética': 'Define los conceptos importantes y acompáñalos de ejemplos cotidianos sobre derechos, responsabilidades y convivencia.',
    'Inglés': 'Practica vocabulario en frases completas y repasa los verbos con ejemplos en presente, pasado y futuro.'
  };
  document.querySelectorAll('[data-subject]').forEach(btn => btn.addEventListener('click', () => {
    const name = btn.dataset.subject;
    showView('materias');
    document.getElementById('subjectDetails').innerHTML = '<h3>' + name + '</h3><p>' + subjectInfo[name] + '</p><p class="bloodline">Expediente abierto.</p><button class="btn" id="subjectNote">Crear recordatorio</button>';
    document.getElementById('subjectNote').addEventListener('click', () => {
      showView('notas');
      const area = document.getElementById('notesArea');
      area.value += (area.value ? '\\n\\n' : '') + 'Recordatorio — ' + name + ': ';
      area.focus();
      notify('Escribe tu recordatorio y guarda tus notas.');
    });
  }));

  const taskList = document.getElementById('taskList');
  function bindTask(task) {
    const checkbox = task.querySelector('input[type="checkbox"]');
    checkbox.checked = task.classList.contains('done');
    checkbox.addEventListener('change', () => {
      task.classList.toggle('done', checkbox.checked);
      saveTasks();
    });
  }
  function saveTasks() {
    const tasks = [...taskList.querySelectorAll('.task')].map(t => ({
      text: t.querySelector('span').textContent,
      date: t.querySelector('time')?.textContent || '',
      done: t.querySelector('input').checked
    }));
    localStorage.setItem('pesadilla_tasks', JSON.stringify(tasks));
  }
  function loadTasks() {
    const saved = localStorage.getItem('pesadilla_tasks');
    if (!saved) { taskList.querySelectorAll('.task').forEach(bindTask); return; }
    try {
      const tasks = JSON.parse(saved);
      taskList.innerHTML = '';
      tasks.forEach(item => {
        const label = document.createElement('label');
        label.className = 'task' + (item.done ? ' done' : '');
        const cb = document.createElement('input'); cb.type = 'checkbox'; cb.checked = !!item.done;
        const span = document.createElement('span'); span.textContent = item.text;
        const time = document.createElement('time'); time.textContent = item.date;
        label.append(cb, span, time); taskList.append(label); bindTask(label);
      });
    } catch { taskList.querySelectorAll('.task').forEach(bindTask); }
  }
  loadTasks();
  document.getElementById('addTask').addEventListener('click', () => {
    const input = document.getElementById('taskInput');
    const value = input.value.trim();
    if (!value) { notify('Escribe el nombre de la tarea primero.'); input.focus(); return; }
    const label = document.createElement('label'); label.className = 'task';
    const cb = document.createElement('input'); cb.type = 'checkbox';
    const span = document.createElement('span'); span.textContent = value;
    const time = document.createElement('time'); time.textContent = '—';
    label.append(cb, span, time); taskList.append(label); bindTask(label); saveTasks();
    input.value = ''; notify('Tarea añadida al expediente.');
  });
  document.getElementById('taskInput').addEventListener('keydown', e => {
    if (e.key === 'Enter') document.getElementById('addTask').click();
  });

  const quotes = [
    '“A veces, lo más oscuro de la mente es lo que nos lleva a la luz.”',
    '“El miedo se hace pequeño cuando te preparas.”',
    '“Cada página que estudias abre una puerta.”',
    '“No necesitas saberlo todo; necesitas empezar.”',
    '“La disciplina es una linterna en los pasillos más oscuros.”'
  ];
  document.getElementById('newQuote').addEventListener('click', () => {
    const q = quotes[Math.floor(Math.random() * quotes.length)];
    document.getElementById('quote').innerHTML = '';
    document.getElementById('quote').append(document.createTextNode(q));
    const small = document.createElement('small'); small.textContent = '— Archivo anónimo';
    document.getElementById('quote').append(small);
  });
  const tips = [
    'Prueba 25 minutos de estudio y 5 minutos de descanso.',
    'Explica el tema en voz alta como si se lo enseñaras a alguien.',
    'Deja preparada tu mochila y tus materiales desde la noche anterior.',
    'Prioriza la tarea más próxima y divide los proyectos grandes en pasos.'
  ];
  document.getElementById('studyTip').addEventListener('click', () => {
    document.getElementById('tipText').textContent = tips[Math.floor(Math.random() * tips.length)];
  });

  const resourceUrls = {
    'Drive': 'https://drive.google.com/',
    'Classroom': 'https://classroom.google.com/',
    'YouTube': 'https://www.youtube.com/',
    'CONALEP': 'https://www.conalep.edu.mx/'
  };
  document.querySelectorAll('[data-resource]').forEach(btn => btn.addEventListener('click', () => {
    const name = btn.dataset.resource;
    if (resourceUrls[name]) {
      if (confirm('¿Quieres abrir ' + name + ' en una pestaña nueva?')) window.open(resourceUrls[name], '_blank', 'noopener,noreferrer');
    } else notify('Recurso seleccionado: ' + name + '. Añade aquí el enlace que utilices.');
  }));

  document.getElementById('saveNotes').addEventListener('click', () => {
    localStorage.setItem('pesadilla_notes', document.getElementById('notesArea').value);
    notify('Tus notas quedaron guardadas en este navegador.');
  });
  document.getElementById('clearNotes').addEventListener('click', () => {
    if (confirm('¿Borrar todas tus notas guardadas?')) {
      document.getElementById('notesArea').value = '';
      localStorage.removeItem('pesadilla_notes');
      notify('Notas borradas.');
    }
  });
  document.getElementById('notesArea').value = localStorage.getItem('pesadilla_notes') || '';
  document.getElementById('lightToggle').addEventListener('click', () => {
    document.body.classList.toggle('lights-on');
    localStorage.setItem('pesadilla_lights', document.body.classList.contains('lights-on') ? 'on' : 'off');
    notify(document.body.classList.contains('lights-on') ? 'Modo claro activado.' : 'Modo oscuro activado.');
  });
  if (localStorage.getItem('pesadilla_lights') === 'on') document.body.classList.add('lights-on');
  document.getElementById('resetTasks').addEventListener('click', () => {
    if (confirm('¿Desmarcar todas las tareas?')) {
      taskList.querySelectorAll('input[type="checkbox"]').forEach(cb => {
        cb.checked = false; cb.closest('.task').classList.remove('done');
      });
      saveTasks(); notify('Todas las tareas se han restablecido.');
    }
  });
</script>
</body>
</html>
