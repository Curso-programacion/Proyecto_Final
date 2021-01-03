Proyecto final
================

# 1 Ojetivo

El objetivo del trabajo final es el realizar una presentación grupal,
donde usando generen el mejor modelo posible para explicar los patrones
de Riqueza de especies de aves encontrados en el sur de Chile, en las
regiones de Araucanía, Los Lagos y Los Ríos (ver figura
<a href="#fig:Diversidad">1.1</a>). Los datos del número de especies en
cada uno de los sitos puede ser encontrado en el archivo
`Diversidad.shp`. Para esto y como variables disponibles pueden usar la
base de datos espaciales `Stack.rds`, los cuales pueden ser visualizados
en la figura <a href="#fig:Variables">1.2</a>). Las variables en este
stack son el indice de modificación humana (Kennedy et al. 2019) y por
otro lado la variables bioclimáticas temperatura media anual, el rango
térmico diario, la precipitación anual y la estacionalidad de la
precipitación descargadas desde worlclim usando el paquete raster en R
(Hijmans 2020). Si bién esas son las variables entregadas, no es
necesario que se restrinjan a solo utilizar estas y pueden agregar otras
que crean
importantes.

<div class="figure">

<img src="README_files/figure-gfm/Diversidad-1.png" alt="Número de especies de aves en el sur de Chile de acuerdo a la distribución de especies determinada por la IUCN"  />

<p class="caption">

Figura 1.1: Número de especies de aves en el sur de Chile de acuerdo a
la distribución de especies determinada por la
IUCN

</p>

</div>

<div class="figure">

<img src="README_files/figure-gfm/Variables-1.png" alt="Mapa con las variables explicativas, las cuales consideran el indice de modificación humana, temperatura media anual, el rango térmico diario, la precipitación anual y la estacionalidad de la precipitación"  />

<p class="caption">

Figura 1.2: Mapa con las variables explicativas, las cuales consideran
el indice de modificación humana, temperatura media anual, el rango
térmico diario, la precipitación anual y la estacionalidad de la
precipitación

</p>

</div>

# 2 Instrucciones

## 2.1 Requisitos mínimos de presentación

  - Presentación de 10 minutos vía Zoom
  - Probar distintos modelos para
  - Entre los resultados entregados deben tener un raster para el área
    realizados en base a una
    [interpolación](https://youtu.be/AjWvI9P6jos)

## 2.2 Material extra disponible

  - Si quieren generar una presentación de forma reproducible (no es
    obligatorio), pueden ver la siguiente [guía
    online](https://bookdown.org/yihui/rmarkdown/presentations.html) y/o
    ver el siguiente
video

<iframe width="560" height="315" src="https://www.youtube.com/embed/2fg_X0d6SRA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>

</iframe>

  - Otros tutoriales espaciales
    [interesantes](https://youtu.be/dQw4w9WgXcQ)

# 3 Referencias

<div id="refs" class="references">

<div id="ref-Hijman2020">

Hijmans, Robert J. 2020. *Raster: Geographic Data Analysis and
Modeling*. <https://CRAN.R-project.org/package=raster>.

</div>

<div id="ref-kennedy2019managing">

Kennedy, Christina M, James R Oakleaf, David M Theobald, Sharon
Baruch-Mordo, and Joseph Kiesecker. 2019. “Managing the Middle: A Shift
in Conservation Priorities Based on the Global Human Modification
Gradient.” *Global Change Biology* 25 (3). Wiley Online Library: 811–26.

</div>

</div>
