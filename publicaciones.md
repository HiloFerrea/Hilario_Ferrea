<nav class="menu">
  <a href="index">Inicio</a>
  <a href="proyectos">Proyectos</a>
  <a href="publicaciones">Publicaciones</a>
  <a href="docencia">Docencia</a>
  <a href="index#contacto">Contacto</a>
</nav>

<hr>

<style>
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

.project-links a + a::before{
  content:"|";
  margin:0 0.4rem;
  color:#9aa0a6;
}
  
</style>




# Publicaciones

<p style="font-size:0.95rem; text-align: justify;">
En esta sección se reúnen informes, documentos metodológicos, presentaciones y materiales de difusión vinculados a proyectos de análisis y producción de información para políticas públicas.
</p>

<div class="pub-box">
  <h2>Informes y documentos</h2>

  <div class="pub-item">
    <p class="pub-title">Título del documento</p>
    <div class="pub-links">
      <a href="{{ site.baseurl }}/docs/archivo.pdf">PDF</a>
      <a href="https://..." target="_blank">Enlace</a>
    </div>
    <p class="pub-meta">Año · Institución/Evento · Tema</p>
  </div>

</div>

<div class="pub-box">
  <h2>Presentaciones</h2>

  <div class="pub-item">
    <p class="pub-title">Título de la presentación</p>
    <div class="pub-links">
      <a href="{{ site.baseurl }}/docs/presentacion.pdf">PDF</a>
    </div>
    <p class="pub-meta">Año · Jornadas/Curso · Tema</p>
  </div>

</div>

<div class="project-box">

  <h2>Pobreza multidimensional</h2>

  <p style="font-size:0.95rem; text-align: justify;">
    Implementación de una medición de pobreza multidimensional en la provincia de Buenos Aires, en articulación con UNICEF, que incorpora una etapa cualitativa basada en el <strong>método consensual</strong> para validar indicadores desde las percepciones de la población y complementar las mediciones tradicionales con un enfoque centrado en el bienestar.
  </p>

  <div style="font-size:0.9rem; margin-top:0.4rem;">
    <p style="margin:0 0 0.3rem 0;"><strong>Presentación</strong></p>

    <div class="project-links">
      <a href="{{ site.baseurl }}/docs/JORNADAS_SAN_MARTIN_FINAL.pdf"> 
      Presentación en jornadas (PDF)
      </a>
    </div>
  </div>

</div>

<div class="project-box">

