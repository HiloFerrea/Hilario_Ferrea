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
  background:#ffffff;
}

.project-box h2{
  margin-top:0;
}
  
</style>


# Proyectos y trabajos

En esta sección se presentan proyectos de análisis, producción de indicadores
y desarrollos aplicados en el ámbito de las políticas públicas.


<div class="project-box">

<h2>Pobreza multidimensional</h2>

<p style="font-size:0.95rem; text-align: justify;">
Implementación de una medición de pobreza multidimensional en la provincia de Buenos Aires, en articulación con UNICEF, que incorpora una etapa cualitativa basada en el <strong>método consensual</strong> para validar indicadores desde las percepciones de la población y complementar las mediciones tradicionales con un enfoque centrado en el bienestar.
</p>

<p><strong>Presentación</strong></p>
<ul>
  <li><a href="docs/JORNADAS_SAN_MARTIN_FINAL.pdf">Presentación en jornadas (PDF)</a></li>
</ul>

</div>




## Canasta de crianza
<p style="font-size:0.95rem; text-align: justify;">
El proyecto desarrolla una metodología y una herramienta de cálculo para estimar el <strong>costo mensual de la crianza</strong> de niñas, niños y adolescentes, integrando el costo de bienes y servicios y la valorización del tiempo de cuidado no remunerado. La estimación contempla diferencias por edad y economías de escala en hogares con más de un NNA, y se orienta al análisis de las condiciones económicas de los hogares y al diseño de políticas públicas.
</p>

**Metodologia**
- [Estimación del costo de la crianza en la provincia de Buenos Aires](docs/CANASTA_CRIANZA_METODOLOGIA__PBA.pdf)  

**Herramientas**
- [Calculadora de Crianza PBA (aplicación)](https://calculadora-crianza-pba-2025.streamlit.app/)


## Esimador de pobreza e indigencia
<p style="font-size:0.95rem; text-align: justify;">
Aplicación desarrollada en Streamlit que permite estimar la situación de pobreza e indigencia de un hogar a partir de su composición  y del ingreso total declarado, replicando la metodología oficial del INDEC. La herramienta calcula las brechas entre los ingresos del hogar y los valores de la Canasta Básica Alimentaria (CBA) y la Canasta Básica Total (CBT), y aporta elementos de análisis al contrastar la estimación objetiva con la percepción subjetiva de la situación económica del hogar.
</p>

- [Calculadora de Pobreza (aplicación)](https://calculadora-pobreza-kkrth2pzeur55gpt2yk2kf.streamlit.app/)


## Indicadores socioeconómicos
Producción de informes y tableros a partir de encuestas de hogares y registros administrativos.
