<!-- ====== ESTILOS LOCALES (no requiere html aparte) ====== -->
<style>
  :root{
    --brand:#0A66C2;        /* azul LinkedIn */
    --brand-2:#22c55e;      /* verde CV */
    --ink:#0f172a;          /* texto */
    --muted:#64748b;        /* texto suave */
    --bg:#f8fafc;           /* fondo secciones */
    --card:#ffffff;
    --shadow:0 10px 25px rgba(2,6,23,.06);
    --radius:16px;
  }
  .hero{
    position:relative; overflow:hidden; border-radius:var(--radius);
    background:linear-gradient(120deg, rgba(10,102,194,.12), rgba(34,197,94,.08));
    padding:40px 24px; box-shadow:var(--shadow); margin:8px 0 24px;
  }
  .hero-inner{max-width:980px;margin:auto;display:grid;grid-template-columns:120px 1fr;gap:24px;align-items:center}
  .hero h1{margin:0;color:var(--ink);font-size:40px;line-height:1.1}
  .hero p{margin:.25rem 0 1rem;color:var(--muted)}
  .avatar{width:120px;height:120px;border-radius:999px;object-fit:cover;border:4px solid #fff;box-shadow:var(--shadow)}
  .badges a{display:inline-block;margin-right:8px;margin-bottom:8px;text-decoration:none}
  .btn{background:var(--brand);color:#fff;padding:10px 14px;border-radius:999px;font-weight:600}
  .btn.ghost{background:#fff;color:var(--brand);border:1px solid var(--brand)}
  .btn.green{background:var(--brand-2)}
  .section{background:var(--bg);padding:20px;border-radius:var(--radius);box-shadow:var(--shadow);margin:24px 0}
  .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:16px}
  .card{background:var(--card);border-radius:var(--radius);box-shadow:var(--shadow);padding:14px}
  .card img{width:100%;border-radius:12px}
  .pill{display:inline-block;padding:4px 10px;border-radius:999px;background:#e9f3ff;color:var(--brand);font-size:12px;margin-left:6px}
  .kpis{display:flex;gap:16px;flex-wrap:wrap}
  .kpi{background:#fff;border-radius:12px;box-shadow:var(--shadow);padding:12px 16px;min-width:160px}
  blockquote{border-left:4px solid var(--brand);padding-left:12px;color:var(--muted)}
  .timeline li{margin-bottom:10px}
</style>

<!-- ====== HERO ====== -->
<div class="hero">
  <div class="hero-inner">
    <img src="assets/avatar.png" alt="Dante Dupeyron" class="avatar">
    <div>
      <h1>Data Analyst</h1>
      <p>Transformo datos en decisiones claras · Python · SQL · Tableau</p>
      <div class="badges">
        <a class="btn" href="https://www.linkedin.com/in/tu-usuario" target="_blank">LinkedIn</a>
        <a class="btn ghost" href="https://github.com/DANTEDUPEYRON21" target="_blank">GitHub</a>
        <a class="btn green" href="CV-DANTE.pdf" target="_blank">CV (PDF)</a>
        <a class="btn ghost" href="mailto:tuemail@correo.com">Email</a>
      </div>
    </div>
  </div>
</div>

<!-- ====== SOBRE MÍ + KPIs ====== -->
## Sobre mí
Ex-hostelería con 8 años en entornos de alta presión. Hoy construyo análisis y dashboards que responden preguntas de negocio. Me enfoco en **limpieza/EDA**, **SQL analítico**, **Tableau** y **pruebas A/B**.

<div class="kpis">
  <div class="kpi"><strong>+6</strong><br>proyectos en GitHub</div>
  <div class="kpi"><strong>3</strong><br>dashboards en Tableau</div>
  <div class="kpi"><strong>8 años</strong><br>liderando equipos</div>
  <div class="kpi"><strong>EN/ES</strong><br>inglés y español fluido</div>
</div>

<!-- ====== PROYECTOS (grid visual con capturas) ====== -->
## Proyectos destacados
<div class="grid">

  <div class="card">
    <img src="assets/proj-churn.png" alt="Modelo de churn">
    <h3>Predicción de churn <span class="pill">ML</span></h3>
    <p>Modelo para detectar riesgo de cancelación. Python, pandas, scikit-learn, SQL.</p>
    <a href="https://github.com/DANTEDUPEYRON21/tu-repo-churn" target="_blank">Ver en GitHub →</a>
  </div>

  <div class="card">
    <img src="assets/proj-ab.png" alt="A/B Recommender">
    <h3>A/B recommender <span class="pill">A/B</span></h3>
    <p>Evaluación del embudo con experimento de recomendaciones. Conversión por etapa.</p>
    <a href="https://github.com/DANTEDUPEYRON21/tu-repo-ab" target="_blank">Ver en GitHub →</a>
  </div>

  <div class="card">
    <img src="assets/proj-sql.png" alt="SQL insights">
    <h3>SQL business insights <span class="pill">SQL</span></h3>
    <p>Consultas para detectar drivers de ingresos y comportamiento de usuarios.</p>
    <a href="https://github.com/DANTEDUPEYRON21/tu-repo-sql" target="_blank">Ver en GitHub →</a>
  </div>

</div>

<!-- ====== FORTALEZAS con íconos/emoji ====== -->
## Fortalezas
- 📊 **Análisis con foco en negocio**: respondo preguntas de impacto.
- 🧽 **Limpieza/EDA**: datos listos para decidir.
- 🐍 **Python**: pandas, numpy, scikit-learn.
- 🧮 **SQL**: joins, ventanas, CTEs, métricas.
- 📈 **Tableau**: dashboards claros y accionables.
- ✅ **Comunicación**: presentaciones ejecutivas, storytelling simple.

<!-- ====== TIMELINE simple ====== -->
## Experiencia (resumen)
<ul class="timeline">
  <li><strong>2025–actual</strong> · Data projects & dashboards en GitHub</li>
  <li><strong>2024–2025</strong> · Certificado en Data Analytics (TripleTen)</li>
  <li><strong>2017–2025</strong> · Royal Caribbean · liderazgo y operaciones</li>
</ul>

<!-- ====== TESTIMONIO (opcional) ====== -->
> “Dante convierte datos en decisiones concretas. Entiende el negocio y lo demuestra en sus dashboards.”

<!-- ====== CTA final ====== -->
<div class="section">
  <h3>¿Buscas un Data Analyst Junior?</h3>
  <p>Estoy listo para contribuir desde el día uno. Escríbeme y revisamos tus KPIs.</p>
  <div class="badges">
    <a class="btn" href="mailto:tuemail@correo.com">Contactar</a>
    <a class="btn ghost" href="https://github.com/DANTEDUPEYRON21?tab=repositories" target="_blank">Ver todos mis proyectos</a>
  </div>
</div>

<!-- ====== TECH STACK BADGES (shields.io) ====== -->
<p align="center">
  <img src="https://img.shields.io/badge/Python-🐍-0A66C2?labelColor=0B1220" />
  <img src="https://img.shields.io/badge/SQL-joins%20%7C%20CTEs-0A66C2?labelColor=0B1220" />
  <img src="https://img.shields.io/badge/Tableau-dashboards-0A66C2?labelColor=0B1220" />
  <img src="https://img.shields.io/badge/pandas-dataframe-0A66C2?labelColor=0B1220" />
</p>

