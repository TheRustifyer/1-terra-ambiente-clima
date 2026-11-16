---
title: Circulación atmosférica y oceánica
asignatura: Terra, Ambiente e Clima
rama:
  - Dinámica atmosférica
  - Oceanografía física
tipo:
  - teoría
  - procedimiento
nivel: universitario-introductorio
estado: borrador
capa: curricular
requiere:
  - "[[Física/Grado/1º/Terra, Ambiente e Clima/02 Balance radiativo y atmósfera|Balance radiativo y atmósfera]]"
fsrs_goal: Explicar la circulación general a partir del calentamiento desigual y la rotación; derivar e interpretar el viento geostrófico; distinguir los mecanismos de circulación oceánica superficial y profunda.
tags:
  - fisica
  - clima
  - atmosfera
  - oceano
  - fcul
  - curricular
---


# Circulación atmosférica y oceánica

El promedio planetario del balance radiativo oculta una desigualdad decisiva: las latitudes bajas reciben más energía solar que las altas. La atmósfera y el océano redistribuyen parte de ese excedente. El movimiento resultante depende del gradiente térmico, de la presión, de la rotación terrestre y de los intercambios con la superficie.<sup><a href="https://science.nasa.gov/earth/earth-observatory/climate-and-earths-energy-budget/">1</a></sup> La circulación general describe ese transporte en promedio; la dinámica de una parcela de aire y las corrientes oceánicas muestran mecanismos concretos.

## Del calentamiento desigual a los vientos dominantes

Si la Tierra no girase, el aire calentado en los trópicos tendería a ascender y a avanzar hacia latitudes altas, mientras aire más frío regresaría cerca de la superficie. La rotación desvía los movimientos horizontales y la circulación observada adopta, como esquema medio por hemisferio, células de **Hadley**, **Ferrel** y **polar**. Los alisios, los vientos del oeste y los vientos polares del este son manifestaciones superficiales de esa organización.<sup><a href="https://scied.ucar.edu/learning-zone/how-weather-works/global-air-atmospheric-circulation">3</a></sup>

> [!definicion] Circulación general atmosférica
> Patrón estadístico de movimientos de gran escala que transporta masa, energía y humedad entre regiones, impulsado por el calentamiento desigual y modificado por la rotación de la Tierra.<sup><a href="https://scied.ucar.edu/learning-zone/how-weather-works/global-air-atmospheric-circulation">3</a></sup>

Las tres células son una representación media, no paredes que impidan el intercambio. Sistemas meteorológicos y corrientes en chorro transportan también energía; por ello una instantánea del viento no tiene por qué parecerse al esquema zonal.<sup><a href="https://scied.ucar.edu/learning-zone/how-weather-works/global-air-atmospheric-circulation">3</a></sup><sup><a href="https://www.meted.ucar.edu/tropical/textbook_2nd_edition/print_3.htm">4</a></sup>

## Dinámica horizontal de una partícula de aire

En un marco que gira con la Tierra, la aceleración horizontal de una parcela de densidad $\rho$ puede escribirse, en una versión simplificada,

$$
\frac{D\mathbf v_h}{Dt}
=-\frac{1}{\rho}\nabla_h p-f\,\mathbf k\times\mathbf v_h+\mathbf a_{\mathrm{roz}},
$$

donde $\mathbf v_h$ es la velocidad horizontal, $p$ la presión, $\nabla_h p$ su gradiente horizontal, $\mathbf k$ la vertical local, $f=2\Omega\sin\varphi$ el parámetro de Coriolis, $\Omega$ la velocidad angular terrestre, $\varphi$ la latitud y $\mathbf a_{\mathrm{roz}}$ la aceleración por rozamiento. El primer término acelera de presión alta a baja; el de Coriolis cambia la dirección del movimiento; el rozamiento importa sobre todo cerca de la superficie. Todos los términos tienen unidades de $\mathrm{m\,s^{-2}}$.<sup><a href="https://www.weather.gov/media/zhu/ZHU_Training_Page/Met_Tutorials/Forecasters_Reference_Book_1997.pdf">5</a></sup>

> [!definicion] Parámetro de Coriolis
> $f=2\Omega\sin\varphi$, con unidades $\mathrm{s^{-1}}$. Su signo cambia entre hemisferios y se anula en el ecuador; su uso en una dinámica horizontal local supone una escala espacial para la que $f$ puede tratarse aproximadamente constante.<sup><a href="https://www.weather.gov/media/zhu/ZHU_Training_Page/Met_Tutorials/Forecasters_Reference_Book_1997.pdf">5</a></sup>

### El límite geostrófico

Lejos de la fricción superficial, si el movimiento horizontal es casi estacionario y la curvatura de la trayectoria es pequeña, los dos términos dominantes pueden compensarse:

$$
0=-\frac{1}{\rho}\nabla_h p-f\,\mathbf k\times\mathbf v_g,
\qquad
\mathbf v_g=\frac{1}{\rho f}\,\mathbf k\times\nabla_h p.
$$

Con $x$ hacia el este e $y$ hacia el norte, $u_g=-(\rho f)^{-1}\partial p/\partial y$ y $v_g=(\rho f)^{-1}\partial p/\partial x$. Por eso el viento geostrófico discurre **paralelo a las isobaras**: el gradiente de presión es perpendicular a ellas. En el hemisferio norte, la presión menor queda a la izquierda del movimiento. La rapidez aumenta cuando las isobaras están más juntas, si $\rho$ y $f$ son comparables.<sup><a href="https://www.weather.gov/media/zhu/ZHU_Training_Page/Met_Tutorials/Forecasters_Reference_Book_1997.pdf">5</a></sup><sup><a href="https://forecast.weather.gov/glossary.php?word=Geostrophic+Wind">6</a></sup>

> [!definicion] Viento geostrófico
> Viento horizontal ideal para el cual la aceleración de Coriolis compensa la fuerza debida al gradiente horizontal de presión. Es una aproximación de gran escala, lejos del rozamiento y del ecuador; no describe bien el viento junto al suelo ni trayectorias muy curvadas.<sup><a href="https://www.weather.gov/media/zhu/ZHU_Training_Page/Met_Tutorials/Forecasters_Reference_Book_1997.pdf">5</a></sup>

```anki
deck: Física::Terra, Ambiente e Clima::Circulación
tags:
  - fisica
  - atmosfera
  - viento-geostrofico
---
> [!note] Pregunta
> ¿Qué dos términos se equilibran en el viento geostrófico y por qué fluye paralelo a las isobaras?
===
> [!important] Respuesta
> Se equilibran gradiente horizontal de presión y aceleración de Coriolis; esta es perpendicular al viento y el gradiente es perpendicular a las isobaras.
```

## Dos vías de circulación oceánica

### Corrientes superficiales

> [!definicion] Circulación oceánica superficial
> Movimiento de la capa superior del océano impulsado principalmente por el esfuerzo del viento y organizado por Coriolis, la geometría de las costas y los gradientes de presión.<sup><a href="https://oceanexplorer.noaa.gov/ocean-fact/currents/">7</a></sup>

Los vientos transfieren momento al mar. En un giro subtropical, la dirección de las corrientes no se deduce sólo del viento local: intervienen rotación y continentes. El transporte de Ekman integra el movimiento de una capa sometida al viento y a la rotación; cuando aleja agua de una costa, puede provocar **afloramiento** de agua subsuperficial. Esa respuesta muestra el acoplamiento entre atmósfera y océano.<sup><a href="https://oceanexplorer.noaa.gov/ocean-fact/currents/">7</a></sup>

### Circulación profunda

> [!definicion] Circulación profunda o de vuelco
> Movimiento de masas de agua que conecta superficie y profundidad, influido por diferencias de densidad asociadas a temperatura y salinidad, junto con mezcla y vientos. La formación de agua densa en altas latitudes alimenta parte de ese movimiento.<sup><a href="https://oceanservice.noaa.gov/education/tutorial_currents/05conveyor1.html">8</a></sup>

Una corriente superficial transporta agua y calor relativamente deprisa; la renovación profunda ocurre en escalas mucho mayores. La conocida imagen de una «cinta transportadora» ayuda a orientarse, pero simplifica una circulación con múltiples rutas, mezcla y variabilidad. Conviene distinguir **mecanismo impulsor**, **profundidad** y **escala temporal** al comparar ambas.<sup><a href="https://oceanexplorer.noaa.gov/ocean-fact/currents/">7</a></sup><sup><a href="https://oceanservice.noaa.gov/education/tutorial_currents/05conveyor1.html">8</a></sup>

El aire y el océano completan el transporte de energía entre regiones. A escalas geológicas, [[Física/Grado/1º/Terra, Ambiente e Clima/04 Dinámica de la geosfera|la geosfera]] modifica además el relieve y los flujos de carbono que condicionan ese sistema.

## Ejemplo: leer un gradiente de presión

En el hemisferio norte, si la presión aumenta hacia el este, $\partial p/\partial x>0$ y $f>0$. Las componentes geostróficas indican $v_g>0$: el viento ideal sopla hacia el norte y deja la presión menor a su izquierda, al oeste. La conclusión cambia de signo en el hemisferio sur; cerca del ecuador la división por $f$ deja de ser una aproximación útil.

## Práctica guiada

#### Ejercicio 1 — Reconocer el mecanismo

Una corriente costera responde en días a vientos persistentes; en otra región se hunde agua fría y salina. ¿Qué mecanismo domina en cada caso y por qué no conviene llamarlos a ambos «circulación profunda»?

> [!resolucion] Comparación causal
> En la costa domina el esfuerzo del viento sobre la capa superficial, modificado por rotación y costa. En el hundimiento interviene el aumento de densidad por enfriamiento y salinidad; puede alimentar la circulación de vuelco. El **error frecuente** es inferir la profundidad sólo por el sentido horizontal de una flecha en un mapa: hacen falta datos de profundidad y densidad.

## 📚 Fuentes

### Material base aportado

- No se dispone de un PDF de apuntes del curso aportado por el usuario.

### Alcance curricular

- [2. FCUL — Programa de *Terra, Ambiente e Clima* (2026/2027)](https://fenix.ciencias.ulisboa.pt/courses/tacli-0-847504421686971/programa). Secuencia de temas.

### Ampliación académica

- [1. NASA — *Climate and Earth’s Energy Budget*](https://science.nasa.gov/earth/earth-observatory/climate-and-earths-energy-budget/). Transporte de calor.
- [3. UCAR — *Global Atmospheric Circulation*](https://scied.ucar.edu/learning-zone/how-weather-works/global-air-atmospheric-circulation). Células y rotación.
- [4. UCAR MetEd — *Global Circulation*](https://www.meted.ucar.edu/tropical/textbook_2nd_edition/print_3.htm). Limitaciones del esquema medio.
- [5. NOAA/NWS — *Forecasters’ Reference Book*, capítulo de viento](https://www.weather.gov/media/zhu/ZHU_Training_Page/Met_Tutorials/Forecasters_Reference_Book_1997.pdf). Dinámica y equilibrio geostrófico.
- [6. NOAA/NWS — *Geostrophic Wind*](https://forecast.weather.gov/glossary.php?word=Geostrophic+Wind). Definición operativa.
- [7. NOAA Ocean Exploration — *What causes ocean currents?*](https://oceanexplorer.noaa.gov/ocean-fact/currents/). Corrientes superficiales y profundas.
- [8. NOAA Ocean Service — *Thermohaline Circulation*](https://oceanservice.noaa.gov/education/tutorial_currents/05conveyor1.html). Densidad y formación de agua profunda.

## 🧑‍🏫 Prompt para tutor conversacional

Tutoriza a nivel universitario introductorio. Formula una pregunta cada vez y espera la respuesta. Comprueba la cadena calentamiento latitudinal → transporte → células de Hadley, Ferrel y polar. Pide interpretar cada término de $D\mathbf v_h/Dt=-\nabla_hp/\rho-f\mathbf k\times\mathbf v_h+\mathbf a_{\mathrm{roz}}$, sus unidades y la hipótesis que lleva a $\mathbf v_g=(\mathbf k\times\nabla_hp)/(\rho f)$. Corrige el signo hemisférico y el uso indebido del modelo cerca del ecuador o del suelo. Contrasta corrientes oceánicas movidas por viento con circulación profunda influida por densidad; usa pistas graduadas y recuperación activa, sin listas de ejercicios. Conecta al final con la geosfera.
