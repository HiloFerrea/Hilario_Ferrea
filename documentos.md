<nav class="menu">
  <a href="index">Inicio</a>
  <a href="proyectos">Proyectos</a>
  <a href="publicaciones">Publicaciones</a>
  <a href="documentos">Documentos de trabajo</a>
  <a href="transferencia">Transferencia</a>
  <a href="#contacto">Contacto</a>
</nav>

<hr>

<style>
/* Menú superior */
.menu{
  display:flex;
  flex-wrap:wrap;
  gap:.5rem;
  margin:.75rem 0 1.25rem 0;
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

/* Caja de proyecto */
.project-box{
  border:1px solid #e1e4e8;
  border-radius:8px;
  padding:1rem 1.2rem;
  margin-bottom:1.4rem;
  background:#fafbfc;
}

.project-box h2{
  margin-top:0;
}

/* Links de proyecto */
.project-links{
  display:flex;
  justify-content:flex-start;
  gap:0.4rem;
  flex-wrap:wrap;
}

.project-links a{
  text-decoration:none;
  font-size:0.85rem;
  color:#0969da;
}

/* Separador | automático */
.project-links a + a::before{
  content:"|";
  margin:0 0.4rem;
  color:#9aa0a6;
}

/* Embed de Tableau */
.tableau-embed{
  margin-top:0.6rem;
  border:1px solid #e1e4e8;
  border-radius:6px;
  overflow:hidden;
  background:#ffffff;
}
</style>



<h1>Informes técnicos / Documentos de trabajo</h1>

<p style="text-align: justify;">
Este espacio agrupa informes técnicos, documentos de trabajo, tableros interactivos y otros desarrollos analíticos orientados a generar evidencia y claridad para el análisis social y las políticas públicas.
</p>


<div class="project-box">

  <h2>Encuesta Provincial de Consumo Energético Residencial (EPCER 2023)</h2>

  <p style="font-size:0.95rem; text-align: justify;">
    La Encuesta Provincial de Consumo Energético para Uso Residencial (EPCER 2023) tuvo como
    objetivo caracterizar el acceso y los usos de la energía en el sector residencial, así como
    recopilar información fundamental para la estimación del consumo energético en los
    135 municipios de la provincia de Buenos Aires. El proyecto aporta insumos clave para el
    análisis territorial del consumo energético y el diseño de políticas públicas orientadas
    al uso eficiente y equitativo de la energía.
  </p>

  <div class="tableau-embed">
    <iframe
      src="https://public.tableau.com/views/ENERGIA_16995434461600/ENERGA?:showVizHome=no"
      width="100%"
      height="550"
      frameborder="0"
      allowfullscreen>
    </iframe>
  </div>

  <div style="font-size:0.9rem; margin-top:0.4rem;">
    <div class="project-links">
      <a href="{{ site.baseurl }}/docs/EPCER_2023.pdf">
        Informe (PDF)
      </a>
      <a href="https://public.tableau.com/views/ENERGIA_16995434461600/ENERGA" target="_blank">
        Ver tablero en Tableau Public
      </a>
    </div>
  </div>

</div>

<div class="project-box">

  <h2>Evaluación del Programa Hacemos Futuro  </h2>

  <p style="font-size:0.95rem; text-align: justify;">
    Informe final de la evaluación del <strong>Programa Hacemos Futuro</strong>, realizada por la Universidad Nacional de La Plata a través de la Dirección de Gestión de Políticas Públicas, a solicitud del Consejo Nacional de Políticas Sociales. La evaluación tuvo como objetivo contribuir a la comprensión de los procesos de diseño e implementación de la política social en la Argentina, entendiendo la evaluación como una herramienta para fortalecer la calidad de las intervenciones estatales y mejorar las condiciones de vida y el acceso a derechos de la población. 
  </p>

  <div style="font-size:0.9rem; margin-top:0.4rem;">
    <p style="margin:0 0 0.3rem 0;"><strong>Accesos</strong></p>

    <div class="project-links">
      <a href="{{ site.baseurl }}/docs/HACEMOS_FUTURO_2022.pdf"> 
      Descargar PDF
      </a>
    </div>
  </div>
  
</div>

<div class="project-box">

  <h2>Desarrollo de las Cadenas de Valor de la ciudad de Mercedes  </h2>

  <p style="font-size:0.95rem; text-align: justify;">
    El proyecto <strong>Desarrollo de las Cadenas de Valor de la ciudad de Mercedes</strong> continúa la experiencia de Mercedes Produce (Fase I), a partir de la cual se relevó y diagnosticó el entramado industrial local, identificando el grado de desarrollo, las proyecciones y los principales desafíos de sus cadenas de valor.
  </p>

  <div style="font-size:0.9rem; margin-top:0.4rem;">
    <p style="margin:0 0 0.3rem 0;"><strong>Accesos</strong></p>

    <div class="project-links">
      <a href="{{ site.baseurl }}/docs/MERCEDES_2024.pdf"> 
      Descargar PDF
      </a>
    </div>
  </div>
</div>
