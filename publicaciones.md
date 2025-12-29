<nav class="menu">
  <a href="index">Inicio</a>
  <a href="proyectos">Proyectos</a>
  <a href="publicaciones">Publicaciones</a>
  <a href="documentos">Documentos de trabajo</a>
  <a href="docencia">Docencia</a>
  <a href="#contacto">Contacto</a>
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

  <h2>Feminidad del riesgo de pobreza y pobreza extrema en la Argentina</h2>

  <p style="font-size:0.95rem; text-align: justify;">
    El objetivo del artículo es cuantificar la feminidad de la pobreza y la pobreza extrema monetarias en la Argentina en 2022, y analizar los determinantes asociados a las desigualdades de género en el mercado laboral. El análisis muestra que, si las mujeres debieran afrontar los gastos de las canastas básicas con ingresos propios, las brechas de género se profundizan, lo que refleja una mayor vulnerabilidad vinculada a las desigualdades laborales.
  </p>

  <div style="font-size:0.9rem; margin-top:0.4rem;">
    <p style="margin:0 0 0.3rem 0;"><strong>Accesos</strong></p>

    <div class="project-links">
      <a href="https://cerac.unlpam.edu.ar/index.php/pys/article/view/8067/9689" target="_blank">
        Leer artículo
      </a>
      <a href="{{ site.baseurl }}/docs/FEMENIDAD_2024.pdf">
        Descargar PDF
      </a>
    </div>
  </div>

</div>

<div class="project-box">

  <h2>Si se cierran las brechas de género...  </h2>

  <p style="font-size:0.95rem; text-align: justify;">
    Este trabajo plantea estimar el efecto que el cierre de la brecha de género en la participación e ingresos laborales
tendría en la pobreza y en la desigualdad de ingresos de los hogares. Se realiza un ejercicio de simulación con escenarios contrafácticos mediante la metodología de imputación múltiple. Los ejercicios de simulación se realizan para la población de 15 a 65 años de la provincia de Buenos Aires, utilizando
los datos de la Encuesta Permanente a Hogares (EPH) total urbano, para el tercer trimestre de 2022. 
  </p>

  <div style="font-size:0.9rem; margin-top:0.4rem;">
    <p style="margin:0 0 0.3rem 0;"><strong>Accesos</strong></p>

    <div class="project-links">
      <a href="{{ site.baseurl }}/docs/POBLACION_PBA_5.pdf"> 
      Descargar PDF
      </a>
    </div>
  </div>

</div>
