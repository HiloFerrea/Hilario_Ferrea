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

TTrabajamos en la generación y el análisis de <strong>información social en sentido amplio</strong>, combinando datos propios, datos públicos y registros administrativos para producir evidencia, herramientas y capacidades técnicas orientadas al análisis social y al diseño y la evaluación de políticas públicas.
</p>
<hr>
---
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
</style>

<div class="caja-servicios">
  <h3>Generación y diseño de datos</h3>
  <p>
    Diseño conceptual y metodológico de indicadores sociales, incluyendo la definición de variables,
    fuentes y criterios de medición, a partir de datos producidos específicamente para cada proyecto,
    fuentes oficiales y registros administrativos.
  </p>
  <hr>

  <h3>Procesamiento, análisis y georreferenciación de datos</h3>
  <p>
    Limpieza, estandarización, procesamiento y análisis de datos sociales, demográficos y territoriales,
    incorporando técnicas de georreferenciación y análisis espacial cuando la problemática lo requiere.
  </p>
  <hr>
  
  <h3>Análisis aplicado y producción de evidencia</h3>
  <p>
    Elaboración de diagnósticos, informes, visualizaciones y análisis orientados a la comprensión de
    fenómenos sociales y a la toma de decisiones en la gestión pública.
  </p>
  <hr>
  
  <h3>Herramientas y visualizaciones</h3>
  <p>
    Desarrollo de tableros interactivos, gráficos, mapas, calculadoras sociales y prototipos basados
    en datos públicos y propios, pensados para facilitar el uso de la información por parte de equipos
    técnicos y decisores.
  </p>
  <hr>

  <h3>Capacitación y transferencia</h3>
  <p>
    Diseño y dictado de talleres, seminarios y espacios de formación orientados a fortalecer capacidades
    para comprender, producir y usar datos en contextos reales de trabajo.
  </p>
</div>


<style>
  /* Opcional pero recomendado: scroll suave cuando clickeás una etapa */
  html{ scroll-behavior:smooth; }

  .ppdac-wrap{
    display:flex;
    justify-content:center;
    margin:1rem 0 1.2rem 0;
  }

  .ppdac-svg{
    width:min(760px, 100%);
    height:auto;
  }

  .ppdac-seg{
    cursor:pointer;
    transition: opacity .15s ease, filter .15s ease;
  }
  .ppdac-seg:hover{
    opacity:.92;
    filter: brightness(0.98);
  }

  .ppdac-label{
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    font-weight: 700;
    letter-spacing: .08em;
    fill: #ffffff;
  }

  .ppdac-center{
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    font-weight: 700;
    fill: #3b3b3b;
  }

  .ppdac-sub{
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    font-weight: 600;
    fill: #6b7280;
  }
</style>

<div class="ppdac-wrap">
  <svg class="ppdac-svg" viewBox="0 0 800 420" role="img" aria-label="Ciclo PPDAC interactivo">
    <!-- Fondo suave para “sentarse” bien en Cayman -->
    <rect x="0" y="0" width="800" height="420" rx="18" fill="#f8fafc"/>

    <!-- Título (si lo querés sin título, borrá estos dos <text>) -->
    <text x="400" y="55" text-anchor="middle" class="ppdac-sub" font-size="18">
      Ciclo de trabajo (PPDAC)
    </text>

    <!-- Grupo donut -->
    <g transform="translate(210,210)">
      <!-- Parámetros del donut:
           centro (0,0), radio 110, stroke 34
           Se dibuja con círculos y dasharray para 5 segmentos + separaciones -->
      <!-- Circunferencia aprox: 2π*110 ≈ 691.15
           Gap 10 => seg ≈ (691.15-50)/5 = 128.23
           Step = seg + gap = 138.23
      -->

      <!-- Rotamos para que “Problema” arranque arriba -->
      <g transform="rotate(-90)">
        <!-- PROBLEMA (Cayman green) -->
        <a href="#ppdac-problema" aria-label="Problema" tabindex="0">
          <circle class="ppdac-seg" r="110" cx="0" cy="0"
                  fill="none" stroke="#159957" stroke-width="34"
                  stroke-dasharray="128.23 562.92" stroke-dashoffset="0"
                  stroke-linecap="butt"/>
        </a>

        <!-- PLAN (Cayman blue) -->
        <a href="#ppdac-plan" aria-label="Plan" tabindex="0">
          <circle class="ppdac-seg" r="110" cx="0" cy="0"
                  fill="none" stroke="#1e6bb8" stroke-width="34"
                  stroke-dasharray="128.23 562.92" stroke-dashoffset="-138.23"
                  stroke-linecap="butt"/>
        </a>

        <!-- DATOS (azul intermedio) -->
        <a href="#ppdac-datos" aria-label="Datos" tabindex="0">
          <circle class="ppdac-seg" r="110" cx="0" cy="0"
                  fill="none" stroke="#2b7bb9" stroke-width="34"
                  stroke-dasharray="128.23 562.92" stroke-dashoffset="-276.46"
                  stroke-linecap="butt"/>
        </a>

        <!-- ANÁLISIS (azul claro) -->
        <a href="#ppdac-analisis" aria-label="Análisis" tabindex="0">
          <circle class="ppdac-seg" r="110" cx="0" cy="0"
                  fill="none" stroke="#3f8fd2" stroke-width="34"
                  stroke-dasharray="128.23 562.92" stroke-dashoffset="-414.69"
                  stroke-linecap="butt"/>
        </a>

        <!-- CONCLUSIONES (teal) -->
        <a href="#ppdac-conclusiones" aria-label="Conclusiones" tabindex="0">
          <circle class="ppdac-seg" r="110" cx="0" cy="0"
                  fill="none" stroke="#2aa198" stroke-width="34"
                  stroke-dasharray="128.23 562.92" stroke-dashoffset="-552.92"
                  stroke-linecap="butt"/>
        </a>
      </g>

      <!-- Centro -->
      <circle r="78" cx="0" cy="0" fill="#ffffff"/>
      <text x="0" y="-6" text-anchor="middle" class="ppdac-center" font-size="22">PPDAC</text>
      <text x="0" y="18" text-anchor="middle" class="ppdac-sub" font-size="13">clickeá una etapa</text>

      <!-- Etiquetas dentro (posiciones aproximadas, quedan bien responsive) -->
      <text x="0" y="-125" text-anchor="middle" class="ppdac-label" font-size="13">PROBLEMA</text>
      <text x="125" y="-10" text-anchor="middle" class="ppdac-label" font-size="13" transform="rotate(72 125 -10)">PLAN</text>
      <text x="80" y="120" text-anchor="middle" class="ppdac-label" font-size="13" transform="rotate(144 80 120)">DATOS</text>
      <text x="-80" y="120" text-anchor="middle" class="ppdac-label" font-size="13" transform="rotate(-144 -80 120)">ANÁLISIS</text>
      <text x="-125" y="-10" text-anchor="middle" class="ppdac-label" font-size="13" transform="rotate(-72 -125 -10)">CONCLUSIONES</text>
    </g>

    <!-- Leyenda / mapeo (opcional, combina bien con Cayman) -->
    <g font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif" font-size="14" fill="#374151">
      <text x="430" y="140"><tspan font-weight="700">Problema</tspan> → Análisis aplicado y producción de evidencia</text>
      <text x="430" y="170"><tspan font-weight="700">Plan</tspan> → Generación y diseño de datos</text>
      <text x="430" y="200"><tspan font-weight="700">Datos</tspan> → Procesamiento, análisis y georreferenciación</text>
      <text x="430" y="230"><tspan font-weight="700">Análisis</tspan> → Herramientas y visualizaciones</text>
      <text x="430" y="260"><tspan font-weight="700">Conclusiones</tspan> → Capacitación y transferencia</text>
    </g>
  </svg>
</div>

<hr>




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
