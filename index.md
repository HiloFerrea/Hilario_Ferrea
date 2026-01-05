<nav class="menu">
  <a href="index">Inicio</a>
  <a href="proyectos">Proyectos</a>
  <a href="publicaciones">Publicaciones</a>
  <a href="documentos">Documentos de trabajo</a>
  <a href="transferencia">Transferencia</a>
</nav>

<hr>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
.menu{
  display:flex;
  flex-wrap:wrap;
  gap:.5rem;
  margin:.75rem 0 1.25rem 0;
  justify-content:center;   /* centra el menú */
}

.menu a{
  text-decoration:none;
  padding:.42rem .85rem;
  border-radius:10px;
  border:1px solid #d9d9d9;
  background:#ffffff;
  color:#2b6cb0;        /* azul sobrio */
  font-weight:600;
  font-size:.92rem;
}

.menu a:hover{
  background:#f3f4f6;
  border-color:#bdbdbd;
}

.centered-title{
  text-align:center;
}

.caja-servicios{
  border:1px solid #e1e4e8;
  border-radius:8px;
  padding:1rem 1.2rem;
  background:#fafbfc;
  margin:1.2rem 0;
}

.caja-servicios h3{
  text-align:center;
}
  
.caja-servicios p{
  text-align: justify;
  text-justify: inter-word;
  hyphens: auto;
}

.ppdac-list p{
  margin:.35rem 0;
  line-height:1.45;
}

.ppdac-desc{
  color:#6b7280;
  font-size:.9rem;
}


.contact-title{
  margin: .2rem 0 .6rem 0;
  font-weight:600;
  text-align:center;   /* 👈 centra el texto */
}
  
.contact-box{
  display:flex;
  flex-wrap:wrap;
  gap:.6rem;
  justify-content:center;   /* 👈 centra los mails */
}

.contact-mails .contact-item{
  font-size:.9rem;   
}


.contact-row{
  display:flex;
  align-items:flex-start;
  gap:.75rem;
  margin:.35rem 0;
}

.contact-label{
  min-width:70px;
  font-size:.85rem;
  color:#6b7280; /* gris suave */
  font-weight:600;
  line-height:1.9;
}

.contact-icons{
  display:flex;
  align-items:center;
  justify-content:center;
  gap:.6rem;
  margin-top:.45rem;
}

.contact-icons a{
  width:38px;
  height:38px;
  display:flex;
  align-items:center;
  justify-content:center;
  border:1px solid #e1e4e8;
  border-radius:8px;
  background:#ffffff;
  color:#2b6cb0;
  text-decoration:none;
}

.contact-icons a:hover{
  background:#f3f4f6;
  border-color:#bdbdbd;
}

.contact-icons i{
  font-size:1.1rem;
}

.contact-logo{
  height:18px;
  width:auto;
  display:block;
}

  
</style>

<h1 class="centered-title">¿Qué es esto?</h1>

<p style="text-align: justify;">
Disipando la Bruma <strong>no es un portfolio</strong> personal.
Es un espacio de trabajo orientado a transformar datos en evidencia para el análisis social y el diseño de políticas públicas.
</p>
<hr>


<h2 class="centered-title">Qué hacemos</h2>
<p style="text-align: justify;">

Trabajamos en la generación y el análisis de <strong>información social en sentido amplio</strong>, combinando datos propios, datos públicos y registros administrativos para producir evidencia, herramientas y capacidades técnicas orientadas al análisis social y al diseño y la evaluación de políticas públicas.
</p>
<hr>
---
<h2 class="centered-title">El ciclo de resolución de problemas de datos</h2>
 <hr>

<style>
  html{ scroll-behavior:smooth; }

  .ppdac-wrap{
    display:flex;
    justify-content:center;
    margin:1rem 0 1.2rem 0;
  }
  .ppdac-svg{
    width:min(640px, 100%);
    height:auto;
  }

  .ppdac-seg{ cursor:pointer; transition:opacity .15s ease; }
  .ppdac-seg:hover{ opacity:.9; }

  .ppdac-label{
    font-family:-apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    font-weight:800;
    letter-spacing:.08em;
    fill:#ffffff;
    pointer-events:none; /* no bloquea el click */
  }

  .ppdac-center{
    font-family:-apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    font-weight:800;
    fill:#374151;
  }
</style>

<div id="ppdac-ciclo" class="ppdac-wrap">
<svg class="ppdac-svg" viewBox="0 0 520 520" role="img" aria-label="Ciclo PPDAC interactivo">
  <defs>
    <!-- Arcos distintos (uno por fase), radio de texto ~ 170 (centro 260,260).
         Cada arco cubre ~72° y arranca en ángulos separados 72°.
         (Coordenadas ya calculadas para evitar superposición) -->

    <!-- PROBLEMA:  -90° a -18° -->
    <path id="ppdac-arc-problema" d="M260 90 A170 170 0 0 1 421.7 207.5" />

    <!-- PLAN: -18° a 54° -->
    <path id="ppdac-arc-plan" d="M421.7 207.5 A170 170 0 0 1 360.0 397.5" />

    <!-- DATOS: 54° a 126° -->
    <path id="ppdac-arc-datos" d="M360.0 397.5 A170 170 0 0 1 160.0 397.5" />

    <!-- ANÁLISIS: 126° a 198° -->
    <path id="ppdac-arc-analisis" d="M160.0 397.5 A170 170 0 0 1 98.3 207.5" />

    <!-- CONCLUSIONES: 198° a 270° -->
    <path id="ppdac-arc-conclusiones" d="M98.3 207.5 A170 170 0 0 1 260 90" />
  </defs>

  <!-- Segmentos (donut con dasharray) -->
  <!-- Parámetros: r=170, stroke=54, circ≈1068.1, gap=16, seg≈197.6, step≈213.6 -->
  <g transform="rotate(-90 260 260)">
    <a href="#ppdac-problema" aria-label="Problema">
      <circle class="ppdac-seg" cx="260" cy="260" r="170" fill="none"
              stroke="#159957" stroke-width="54"
              stroke-dasharray="197.6 870.5" stroke-dashoffset="0"/>
    </a>
    <a href="#ppdac-plan" aria-label="Plan">
      <circle class="ppdac-seg" cx="260" cy="260" r="170" fill="none"
              stroke="#1e6bb8" stroke-width="54"
              stroke-dasharray="197.6 870.5" stroke-dashoffset="-213.6"/>
    </a>
    <a href="#ppdac-datos" aria-label="Datos">
      <circle class="ppdac-seg" cx="260" cy="260" r="170" fill="none"
              stroke="#2b7bb9" stroke-width="54"
              stroke-dasharray="197.6 870.5" stroke-dashoffset="-427.2"/>
    </a>
    <a href="#ppdac-analisis" aria-label="Análisis">
      <circle class="ppdac-seg" cx="260" cy="260" r="170" fill="none"
              stroke="#3f8fd2" stroke-width="54"
              stroke-dasharray="197.6 870.5" stroke-dashoffset="-640.8"/>
    </a>
    <a href="#ppdac-conclusiones" aria-label="Conclusiones">
      <circle class="ppdac-seg" cx="260" cy="260" r="170" fill="none"
              stroke="#2aa198" stroke-width="54"
              stroke-dasharray="197.6 870.5" stroke-dashoffset="-854.4"/>
    </a>
  </g>

  <!-- Etiquetas: cada una en su arco, centradas, sin superposición -->
  <text class="ppdac-label" font-size="14">
    <textPath href="#ppdac-arc-problema" startOffset="50%" text-anchor="middle">PROBLEMA</textPath>
  </text>

  <text class="ppdac-label" font-size="14">
    <textPath href="#ppdac-arc-plan" startOffset="50%" text-anchor="middle">PLAN</textPath>
  </text>

  <text class="ppdac-label" font-size="14">
    <textPath href="#ppdac-arc-datos" startOffset="50%" text-anchor="middle">DATOS</textPath>
  </text>

  <text class="ppdac-label" font-size="14">
    <textPath href="#ppdac-arc-analisis" startOffset="50%" text-anchor="middle">ANÁLISIS</textPath>
  </text>

  <text class="ppdac-label" font-size="14">
    <textPath href="#ppdac-arc-conclusiones" startOffset="50%" text-anchor="middle">CONCLUSIONES</textPath>
  </text>

  <!-- Centro -->
  <circle cx="260" cy="260" r="110" fill="#ffffff"/>
  <text x="260" y="270" text-anchor="middle" class="ppdac-center" font-size="26">PPDAC</text>
</svg>
</div>



<style>
  .caja-servicios{
    border: 1px solid #e1e4e8;
    border-radius: 10px;
    padding: 1.1rem 1.2rem;
    background: #fafbfc;
    margin: 1.2rem 0;
  }

  .caja-servicios h3{
    margin: 0 0 .35rem 0;
  }

  .caja-servicios p{
    margin: 0 0 1rem 0;
    line-height: 1.45;
  }

  .caja-servicios p:last-child{
    margin-bottom: 0;
  }

.ppdac-stage{
  text-align: center;
}

.volver-ciclo{
  text-align:center;
  margin: .6rem 0 1.4rem 0;
}

.volver-ciclo a{
  font-size:.85rem;
  text-decoration:none;
}

.volver-ciclo a:hover{
  text-decoration:underline;
}

</style>



<h2 id="ppdac-problema" class="ppdac-stage">Problema</h2>
  <hr>
<div class="caja-servicios">
  <h3>Análisis aplicado y producción de evidencia</h3>
  <p>
    Formulación de la pregunta y construcción del diagnóstico. Elaboración de análisis orientados a la comprensión de fenómenos sociales, identificando patrones, brechas y problemáticas relevantes para la gestión pública y la toma de decisiones.
  </p>
  <p class="volver-ciclo">
      <a href="#ppdac-ciclo">↑ Volver al ciclo</a>
  </p>
  <hr>
 </div>

<h2 id="ppdac-plan" class="ppdac-stage">Plan</h2>
  <hr>
<div class="caja-servicios">
  <h3>Generación y diseño de datos</h3>
  <p>
    Diseño conceptual y metodológico de indicadores sociales, incluyendo la definición de variables, fuentes y criterios de medición. Comprende la planificación de datos producidos específicamente para cada proyecto y su articulación con fuentes oficiales y registros administrativos.
  </p>
    <p class="volver-ciclo">
      <a href="#ppdac-ciclo">↑ Volver al ciclo</a>
  </p>
    <hr>
</div>

<h2 id="ppdac-datos" class="ppdac-stage">Datos</h2>
<hr>
<div class="caja-servicios">
   <h3>Procesamiento, análisis y georreferenciación de datos</h3>
   <p>
    Limmpieza, estandarización, procesamiento e integración de datos sociales, demográficos y territoriales. Incorporación de técnicas de georreferenciación y análisis espacial cuando la problemática lo requiere, garantizando la calidad y consistencia de la información.
  </p>
    <p class="volver-ciclo">
      <a href="#ppdac-ciclo">↑ Volver al ciclo</a>
  </p>
  <hr>
</div>

  
<h2 id="ppdac-analisis" class="ppdac-stage">Análisis</h2>
<hr>
<div class="caja-servicios">
    <h3>Herramientas y visualizaciones</h3>
  <p>
    Desarrollo de tableros interactivos, gráficos, mapas, calculadoras sociales y prototipos basados en datos públicos y propios. Transformación de los datos en lectura analítica y visual para facilitar su comprensión, comparación y uso por parte de equipos técnicos y decisores.
  </p>
    <p class="volver-ciclo">
      <a href="#ppdac-ciclo">↑ Volver al ciclo</a>
  </p>
  <hr>
</div>

<h2 id="ppdac-conclusiones" class="ppdac-stage">Conclusiones</h2>
<hr>

<div class="caja-servicios">
     <h3>Capacitación y transferencia</h3>
  <p>
    iseño y dictado de talleres, seminarios y espacios de formación orientados a fortalecer capacidades para comprender, producir y usar datos en contextos reales de trabajo. Transferencia de resultados, métodos y aprendizajes para su incorporación efectiva en procesos de decisión.
  </p>
    <p class="volver-ciclo">
      <a href="#ppdac-ciclo">↑ Volver al ciclo</a>
  </p>
  <hr>
</div>

<hr>

<p class="contact-title">
  Contacto
</p>


<div class="contact-box">
  <a class="contact-item link" href="mailto:hiloferrea@gmail.com"> hiloferrea@gmail.com</a>
  <a class="contact-item link" href="mailto:hferrea@estadistica.ec.gba.gov.ar"> hferrea@estadistica.ec.gba.gov.ar</a>
</div>

<hr>
  
<div class="contact-box contact-icons">

  <!-- LinkedIn -->
  <a href="https://www.linkedin.com/in/hilario-ferrea-544521158"
     target="_blank" rel="noopener" aria-label="LinkedIn">
    <i class="fa-brands fa-linkedin-in"></i>
  </a>

  <!-- GitHub -->
  <a href="https://github.com/HiloFerrea"
     target="_blank" rel="noopener" aria-label="GitHub">
    <i class="fa-brands fa-github"></i>
  </a>

  <!-- Tableau Personal -->
  <a href="https://public.tableau.com/app/profile/hilario.ferrea"
     target="_blank" rel="noopener" aria-label="Tableau Public Personal">
    <img src="assets/img/tableau.svg"
         alt="Tableau Public – Personal"
         class="contact-logo">
  </a>

  <!-- Tableau DPE -->
  <a href="https://public.tableau.com/app/profile/departamento.de.an.lisis.de.estad.sticas.sociales"
     target="_blank" rel="noopener" aria-label="Tableau Public DPE">
    <img src="assets/img/tableau.svg"
         alt="Tableau Public – DPE"
         class="contact-logo">
  </a>

</div>
