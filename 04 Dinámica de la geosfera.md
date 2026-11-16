---
title: Dinámica de la geosfera
aliases:
  - Tectónica, isostasia, vulcanismo y meteorización
asignatura: Terra, Ambiente e Clima
rama:
  - Geofísica
  - Ciencias de la Tierra
tipo:
  - teoría
  - modelo
nivel: universitario-introductorio
estado: borrador
capa: curricular
requiere:
  - "[[01 Sistema climático y registro del clima|Sistema climático y registro del clima]]"
fsrs_goal: Relacionar tipos de límites de placas con procesos geológicos; explicar y calcular una raíz cortical en el modelo de Airy; distinguir el efecto climático breve de los aerosoles volcánicos del ciclo lento de meteorización de silicatos.
tags:
  - fisica
  - geofisica
  - tectonica
  - clima
  - fcul
  - curricular
---


# Dinámica de la geosfera

La geosfera cambia con lentitud frente al tiempo atmosférico, pero determina la configuración de continentes y cuencas, construye relieve y participa en el intercambio de carbono con atmósfera y océano. La tectónica, la isostasia, el vulcanismo y la meteorización conectan esa dinámica interna y superficial con el ambiente de formas y a escalas muy distintas.<sup><a href="https://www.ipcc.ch/report/ar6/wg1/chapter/chapter-5/">3</a></sup>

## Placas y límites

> [!definicion] Placa litosférica
> Fragmento de litosfera rígida que se desplaza respecto de otras placas sobre un interior terrestre capaz de deformarse en escalas geológicas. La litosfera comprende corteza y parte superior del manto; sus límites concentran buena parte de la deformación, sismicidad y actividad volcánica.<sup><a href="https://pubs.usgs.gov/gip/dynamic/understanding.html">2</a></sup>

El **límite divergente** separa placas y crea corteza oceánica en dorsales. En uno **convergente** puede subducir litosfera oceánica, formarse un arco volcánico o colisionar continentes. En uno **transformante** domina el deslizamiento lateral: no se crea ni destruye corteza en el límite ideal. Esta clasificación permite anticipar procesos, sin afirmar que cada volcán o terremoto responda a una única situación.<sup><a href="https://pubs.usgs.gov/gip/dynamic/understanding.html">2</a></sup>

| Límite | Movimiento relativo | Resultado característico |
|---|---|---|
| Divergente | Separación | Dorsal y nueva corteza oceánica |
| Convergente | Aproximación | Subducción o colisión; posible arco volcánico |
| Transformante | Deslizamiento lateral | Fallas y sismicidad |

La tectónica modifica relieve y posición de continentes a largo plazo. Esos cambios alteran las rutas de circulación, la exposición de rocas a meteorización y los lugares donde los volcanes liberan material, pero no proporcionan por sí solos una explicación de cualquier fluctuación climática reciente.<sup><a href="https://pubs.usgs.gov/gip/dynamic/understanding.html">2</a></sup><sup><a href="https://www.ipcc.ch/report/ar6/wg1/chapter/chapter-5/">3</a></sup>

## Isostasia: equilibrio vertical

Una columna cortical elevada puede sostenerse con una raíz de material relativamente ligero que penetra en un manto más denso. La analogía de un bloque flotante ayuda a entender el balance, siempre recordando que el manto sólido se deforma durante tiempos largos y que la Tierra real también tiene resistencia flexural.<sup><a href="https://pubs.usgs.gov/of/1995/0479/report.pdf">4</a></sup>

> [!definicion] Isostasia
> Compensación gravitatoria aproximada de columnas de litosfera: a una profundidad de compensación, diferencias de elevación pueden corresponder a diferencias de espesor o densidad, de modo que las cargas se equilibran.<sup><a href="https://pubs.usgs.gov/of/1995/0479/report.pdf">4</a></sup>

**Airy** supone densidad cortical constante y espesor variable; una montaña posee una raíz más gruesa. **Pratt** supone un espesor hasta la profundidad de compensación aproximadamente constante y densidad lateral variable. Son modelos alternativos de primer orden, no dos capas físicas que deban sumarse sin más.<sup><a href="https://pubs.usgs.gov/of/1995/0479/report.pdf">4</a></sup>

En el modelo de Airy, sean $h$ la altura topográfica, $r$ la profundidad adicional de la raíz, $\rho_c$ la densidad cortical y $\rho_m>\rho_c$ la densidad del manto. Igualar el exceso de masa de la montaña con el déficit de masa de su raíz da

$$
\rho_c h=(\rho_m-\rho_c)r,\qquad
r=\frac{\rho_c}{\rho_m-\rho_c}\,h.
$$

Las densidades deben tener las mismas unidades y $h$ y $r$ son longitudes. Si $\rho_c=2700\ \mathrm{kg\,m^{-3}}$, $\rho_m=3300\ \mathrm{kg\,m^{-3}}$ y $h=1\ \mathrm{km}$, la raíz ideal es $r=4{,}5\ \mathrm{km}$. El resultado muestra por qué una montaña puede tener una compensación subterránea mucho mayor que su altura visible; no predice una raíz real sin conocer estructura y flexión regional.<sup><a href="https://pubs.usgs.gov/of/1995/0479/report.pdf">4</a></sup>

```anki
deck: Física::Terra, Ambiente e Clima::Geosfera
tags:
  - fisica
  - geofisica
  - isostasia
---
> [!note] Pregunta
> En la isostasia de Airy, ¿qué cambia entre una columna cortical elevada y otra de referencia?
===
> [!important] Respuesta
> Cambia el espesor de corteza de densidad aproximadamente constante: la elevación se compensa con una raíz cortical más profunda.
```

## Dos contactos entre geosfera y clima

### Vulcanismo

> [!definicion] Efecto climático volcánico de corto plazo
> Cambio radiativo producido cuando una erupción explosiva inyecta gases, especialmente $SO_2$, en la estratosfera; su conversión en aerosoles de sulfato aumenta la reflexión solar y puede enfriar temporalmente la superficie.<sup><a href="https://www.usgs.gov/programs/VHP/volcanoes-can-affect-climate">5</a></sup>

La ceniza cae comparativamente deprisa; los aerosoles estratosféricos persisten más y dominan el efecto radiativo de grandes erupciones. El $CO_2$ volcánico interviene en el ciclo geológico del carbono, pero no explica el calentamiento humano actual: los flujos contemporáneos volcánicos son mucho menores que los de actividades humanas.<sup><a href="https://www.usgs.gov/programs/VHP/volcanoes-can-affect-climate">5</a></sup>

### Meteorización

> [!definicion] Meteorización
> Alteración y descomposición de rocas expuestas en la superficie. La meteorización **física** fragmenta; la **química** cambia minerales mediante reacciones con agua, gases y solutos.<sup><a href="https://www.ipcc.ch/report/ar6/wg1/chapter/chapter-5/">3</a></sup>

La meteorización química de silicatos consume $CO_2$ en un proceso que, unido al transporte de productos al océano y su eventual enterramiento, participa en la regulación del carbono durante tiempos geológicos. Temperatura, agua y superficie de roca expuesta condicionan su velocidad. La relación se representa de modo esquemático como **silicato + $CO_2$ → productos disueltos → carbonato sedimentario**; la reacción concreta depende del mineral y del recorrido químico, por lo que esa flecha no sustituye un balance estequiométrico.<sup><a href="https://www.ipcc.ch/report/ar6/wg1/chapter/chapter-5/">3</a></sup><sup><a href="https://archive.ipcc.ch/publications_and_data/ar4/wg1/en/ch7s7-3.html">6</a></sup>

Vulcanismo y meteorización conectan la dinámica sólida con el clima en escalas diferentes: una inyección estratosférica puede alterar varios años de radiación; el balance entre desgasificación y retirada de carbono por meteorización opera principalmente a escalas geológicas.<sup><a href="https://www.ipcc.ch/report/ar6/wg1/chapter/chapter-5/">3</a></sup><sup><a href="https://www.usgs.gov/programs/VHP/volcanoes-can-affect-climate">5</a></sup>

## Ejemplo: interpretar una raíz cortical

El cálculo anterior da $r/h=4{,}5$ para las densidades elegidas: por cada kilómetro de elevación, el modelo coloca $4{,}5$ km de raíz adicional. Esta proporción aumenta cuando el contraste $\rho_m-\rho_c$ disminuye. El **caso límite** $\rho_m=\rho_c$ muestra por qué Airy exige un manto más denso: sin contraste de densidad, una raíz de esa corteza no compensaría la montaña.

## Práctica guiada

#### Ejercicio 1 — Distinguir dos escalas climáticas

Una gran erupción inyecta $SO_2$ estratosférico; simultáneamente, una cordillera joven expone silicatos a la lluvia. ¿Qué proceso puede alterar la radiación en los años siguientes y cuál participa en el ciclo lento del carbono?

> [!resolucion] Procesos y tiempos
> El $SO_2$ puede transformarse en aerosol de sulfato que refleje radiación y produzca enfriamiento temporal. La meteorización química de silicatos puede retirar $CO_2$ dentro del ciclo geológico, condicionado por agua, temperatura y exposición de roca. No se debe atribuir a un único episodio de meteorización un efecto climático anual medible sin cuantificar flujos: esa es la **condición de validez** de la comparación de escalas.

## 📚 Fuentes

### Material base aportado

- No se dispone de un PDF de apuntes del curso aportado por el usuario.

### Alcance curricular

- [1. FCUL — Programa de *Terra, Ambiente e Clima* (2026/2027)](https://fenix.ciencias.ulisboa.pt/courses/tacli-0-847504421686971/programa). Temario.
- [7. FCUL — Sumarios del curso 2025/2026](https://fenix.ciencias.ulisboa.pt/courses/tacli-2817829258658062/sumarios). Confirma el tratamiento de Airy y Pratt y de los impactos climáticos del vulcanismo.

### Ampliación académica

- [2. USGS — *Understanding plate motions*](https://pubs.usgs.gov/gip/dynamic/understanding.html). Límites de placas.
- [3. IPCC — *AR6 WGI*, capítulo 5](https://www.ipcc.ch/report/ar6/wg1/chapter/chapter-5/). Ciclo geológico del carbono.
- [4. USGS — *Isostasy*, recuadro 2.2](https://pubs.usgs.gov/of/1995/0479/report.pdf). Modelos de Airy y Pratt.
- [5. USGS — *Volcanoes Can Affect Climate*](https://www.usgs.gov/programs/VHP/volcanoes-can-affect-climate). Aerosoles volcánicos.
- [6. IPCC — *AR4 WGI*, apartado 7.3](https://archive.ipcc.ch/publications_and_data/ar4/wg1/en/ch7s7-3.html). Meteorización de silicatos.

## 🧑‍🏫 Prompt para tutor conversacional

Tutoriza a nivel universitario introductorio, con una pregunta cada vez y espera de respuesta. Evalúa los movimientos divergente, convergente y transformante; distingue placas de continentes. Pide explicar el sentido físico de la compensación isostática y derivar $r=\rho_ch/(\rho_m-\rho_c)$ declarando $\rho_m>\rho_c$, unidades y límites de Airy; contrasta con Pratt. Comprueba que el estudiante atribuye el enfriamiento volcánico breve principalmente al sulfato estratosférico y sitúa la meteorización de silicatos en el ciclo lento del carbono. Corrige con pistas graduadas y evita colecciones de ejercicios.
