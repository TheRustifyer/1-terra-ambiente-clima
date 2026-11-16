---
title: Balance radiativo y atmósfera
aliases:
  - Balanço radiativo
asignatura: Terra, Ambiente e Clima
rama:
  - Física atmosférica
  - Climatología
tipo:
  - teoría
  - modelo
nivel: universitario-introductorio
estado: borrador
capa: curricular
requiere:
  - "[[01 Sistema climático y registro del clima|Sistema climático y registro del clima]]"
fsrs_goal: Derivar la temperatura efectiva desde la geometría y el balance planetario; reconstruir los balances de una capa opaca y una capa parcialmente opaca; interpretar absorción espectral y distinguir los efectos radiativos de nubes y aerosoles con sus límites.
tags:
  - fisica
  - clima
  - radiacion
  - atmosfera
  - fcul
  - curricular
---


# Balance radiativo y atmósfera

La energía que mantiene activo el sistema climático llega sobre todo desde el Sol. La Tierra absorbe una parte, refleja otra y, a su vez, emite radiación térmica al espacio. La atmósfera modifica ese intercambio: deja pasar buena parte de la luz solar, absorbe ciertas longitudes de onda infrarrojas y emite radiación en todas direcciones.

El balance radiativo conecta tres preguntas: qué radiación llega, qué parte absorben o reflejan la superficie y la atmósfera, y qué energía termina escapando al espacio. Esa contabilidad explica la temperatura efectiva del planeta y prepara los modelos sencillos del efecto invernadero. La atmósfera real añade nubes, transporte de calor y variaciones verticales que los modelos más simples dejan fuera. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 3–10, 14–17); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 2–12, 17–18, 30–39).

Las aplicaciones numéricas y conceptuales de la serie se desarrollan en [[Física/Grado/1º/Terra, Ambiente e Clima/02 Ejercicios resueltos — Balance radiativo y atmósfera|Ejercicios resueltos — Balance radiativo y atmósfera]].

## La atmósfera: capas y composición

### Perfil vertical de temperatura

La temperatura no disminuye de forma continua con la altura. En las capas bajas desciende, en la estratosfera vuelve a aumentar, en la mesosfera cae otra vez y en la termosfera crece con rapidez. Esa alternancia da nombre a las principales capas térmicas.

> [!definicion] Capas térmicas de la atmósfera
> La **troposfera** es la capa inferior, donde ocurre la mayor parte del tiempo meteorológico y se concentra cerca del 80 % de la masa atmosférica. La **tropopausa** la separa de la **estratosfera**, en la que el ozono absorbe radiación ultravioleta y la temperatura aumenta con la altura. La **estratopausa** marca el paso a la **mesosfera**, donde la temperatura vuelve a bajar hasta la **mesopausa**. Por encima se encuentra la **termosfera**, en la que la absorción de radiación solar por gases muy diluidos eleva la temperatura. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 1–2).

En el perfil ilustrado por el profesor, la troposfera llega aproximadamente a 10–20 km; la estratosfera se extiende hasta cerca de 50 km; la mesosfera, hasta unos 80–85 km, y la termosfera comienza por encima de unos 90 km. Son alturas orientativas. Cambian con la latitud y la estación, y la gráfica combina escalas no uniformes: una distancia dibujada no representa necesariamente el mismo intervalo de temperatura o altitud en toda la figura. El pie de figura llama tropical a un perfil que el texto describe para latitudes medias; por eso conviene leer sus valores como esquema y no como una curva de referencia única. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 1–2, fig. 2.1).

En el perfil docente, la temperatura ronda 290 K cerca del suelo, alcanza unos 280 K en la estratopausa, cae hasta cerca de $-90\ ^\circ\mathrm C$ hacia los 80 km y puede superar 1000 K por encima de 200 km en la termosfera. El PDF atribuye cerca del 19,9 % de la masa atmosférica a la estratosfera, tras el aproximadamente 80 % de la troposfera. Son cifras del perfil esquemático, no valores universales para todas las latitudes y estaciones. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 1–2, fig. 2.1).

En la troposfera, el texto da un gradiente medio cercano a $6{,}5\ ^\circ\mathrm C\,\mathrm{km}^{-1}$. En la estratosfera, el calentamiento con la altura se relaciona con la absorción ultravioleta del ozono, concentrado sobre todo entre unos 20 y 30 km. En la termosfera, la absorción de radiación por oxígeno molecular calienta una cantidad de aire muy pequeña; por eso la temperatura puede alcanzar valores muy altos sin implicar una gran cantidad de energía térmica por unidad de volumen. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 1–2).

### Gases, vapor, nubes y partículas

El aire seco cerca de la superficie está compuesto principalmente por nitrógeno, oxígeno y argón. La tabla de composición incluye proporciones de los gases mayoritarios y cifras para componentes traza, pero no establece una fecha de medición común. Por ejemplo, informa $0{,}041\ \%$ de $\mathrm{CO_2}$ en la tabla y alrededor de 400 ppm en el texto, ambos valores históricos del material y no una medida actual. Lo importante para el balance no es solo cuánto abunda un gas: también cuenta qué longitudes de onda puede absorber.

| Constituyente del aire seco | Valor tabulado en el PDF (% en volumen) |
|---|---:|
| Nitrógeno, $\mathrm{N_2}$ | 78,084 |
| Oxígeno, $\mathrm{O_2}$ | 20,946 |
| Argón, $\mathrm{Ar}$ | 0,934 |
| Dióxido de carbono, $\mathrm{CO_2}$ | 0,041 |
| Neón, $\mathrm{Ne}$ | $1{,}8\times10^{-5}$ |
| Helio, $\mathrm{He}$ | $5{,}24\times10^{-6}$ |
| Metano, $\mathrm{CH_4}$ | $1{,}7\times10^{-7}$ |
| Kriptón, $\mathrm{Kr}$ | $1{,}13\times10^{-6}$ |
| Óxido nitroso, $\mathrm{N_2O}$ | $3\times10^{-7}$ |
| Xenón, $\mathrm{Xe}$ | $8{,}7\times10^{-8}$ |
| Monóxido de carbono, $\mathrm{CO}$ | $5$–$20\times10^{-8}$ |
| Sulfuro de carbonilo, $\mathrm{OCS}$ | $5\times10^{-10}$ |
| Ozono troposférico, $\mathrm{O_3}$ | $5\times10^{-8}$ a $4\times10^{-7}$ |
| Ozono estratosférico, $\mathrm{O_3}$ | $1\times10^{-7}$ a $6\times10^{-6}$ |

Los porcentajes traza de la tabla se reproducen tal como aparecen, no como concentraciones vigentes. La tabla rotula $\mathrm{N_2O}$ como «óxido nítrico», mientras que el texto lo llama óxido nitroso; aquí se usa el nombre correspondiente a la fórmula y al texto. Además, el porcentaje tabulado para $\mathrm{CH_4}$ no coincide con la concentración descrita más adelante, otra razón para conservar la tabla solo como registro histórico del material. El vapor de agua y el ozono son especialmente variables: el primero predomina en la baja troposfera, mientras que la mayor parte del ozono atmosférico se concentra en la estratosfera. También hay gotas líquidas y cristales de hielo en las nubes, además de polvo, sulfatos y ceniza volcánica en suspensión. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 2–3, tabla 2.I).

La distinción entre gases abundantes y gases radiativamente activos resulta esencial. El nitrógeno, el oxígeno y el argón constituyen casi todo el aire seco, pero sus moléculas no absorben de manera importante la radiación infrarroja terrestre. En cambio, gases mucho menos abundantes sí absorben en bandas concretas del infrarrojo. Las nubes y los aerosoles, aunque no sean gases, también alteran los flujos por reflexión, dispersión y absorción.

## Radiación electromagnética y espectro

### Longitud de onda y energía

La radiación electromagnética transporta energía. Puede describirse como una onda, caracterizada por su longitud de onda $\lambda$ y frecuencia $\nu$, o como un conjunto de fotones. La energía de un fotón es

$$
E_\gamma=h\nu=\frac{hc}{\lambda},
$$

donde $h$ es la constante de Planck, $c$ la velocidad de la luz y $\lambda$ la longitud de onda. A menor longitud de onda, mayor energía por fotón. La radiación gamma, ultravioleta, visible, infrarroja y de radio son regiones de un mismo espectro electromagnético; sus nombres describen rangos de longitud de onda, no naturalezas físicas distintas. Además de radiación, el Sol emite partículas cargadas que forman el viento solar; este interactúa sobre todo con las capas exteriores de las atmósferas. [1](<Cap2_Teoria_29_10_2024.pdf>) (p. 3); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 2).

La radiación solar se concentra en longitudes de onda relativamente cortas, con un máximo en la región visible. La radiación térmica de la Tierra se concentra en longitudes de onda mayores, dentro del infrarrojo. Las diapositivas ilustran el contraste con dos cuerpos: para el Sol, $T\approx5800\ \mathrm K$ y un máximo cercano a $0{,}50\ \mu\mathrm m$; para la Tierra, cerca de $290\ \mathrm K$ y un máximo en torno a $10\ \mu\mathrm m$. Las proporciones de energía que las diapositivas asignan a ultravioleta, visible e infrarrojo —9 %, 49 % y 42 %— son cifras didácticas de ese material, no constantes universales para cualquier definición de bandas. [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 6–7).

### Cuerpo negro y leyes de radiación

> [!definicion] Cuerpo negro
> Un **cuerpo negro ideal** absorbe toda la radiación electromagnética incidente: no refleja ni transmite energía. En equilibrio térmico también emite radiación, y su espectro depende únicamente de la temperatura. Ningún cuerpo real es un absorbente y emisor perfecto, pero el modelo describe bien muchos espectros térmicos. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 4–5); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 3–5).

La ley de Planck describe cuánta energía emite un cuerpo negro en cada intervalo de longitud de onda. En la expresión impresa en el PDF, las constantes se dan en unidades SI mientras que el texto indica $\lambda$ en micrómetros; esa combinación no es dimensionalmente coherente. Aquí se usa una forma consistente en unidades SI, con $\lambda$ en metros. En la forma espectral por longitud de onda,

$$
M_\lambda(T)=\frac{2\pi h c^2}{\lambda^5}\,\frac{1}{\exp\!\left(\frac{hc}{\lambda k_{\mathrm B}T}\right)-1},
$$

donde $M_\lambda$ es la potencia emitida por unidad de superficie y por unidad de longitud de onda, $T$ se mide en kelvin, $\lambda$ en metros, y $k_{\mathrm B}$ es la constante de Boltzmann. Si el eje de una gráfica se expresa en micrómetros, debe convertirse a metros al usar esta forma SI de la ecuación. La figura del capítulo compara curvas para 3000, 4000, 5000 y 6000 K: al aumentar la temperatura, crece el área bajo la curva y el máximo se desplaza hacia longitudes de onda menores. Como ejemplo numérico, el cuerpo a 6000 K emite 16 veces más potencia por unidad de superficie que el mismo cuerpo a 3000 K. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 4–5, fig. 2.3); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 3–5); [4](https://openstax.org/books/university-physics-volume-3/pages/6-1-blackbody-radiation).

La ley de Stefan–Boltzmann resume el área total bajo ese espectro:

$$
F=\sigma T^4,
$$

donde $F$ es la irradiancia emitida por unidad de superficie, en $\mathrm{W\,m^{-2}}$, y $\sigma=5{,}67\times10^{-8}\ \mathrm{W\,m^{-2}\,K^{-4}}$ es la constante de Stefan–Boltzmann. Si se duplica la temperatura absoluta, la irradiancia se multiplica por $2^4=16$. La dependencia con la cuarta potencia hace que una variación térmica modesta pueda cambiar de forma apreciable la energía emitida. [1](<Cap2_Teoria_29_10_2024.pdf>) (p. 4, ec. 2.2); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 3).

> [!definicion] Longitud de onda de Wien
> Para un espectro de cuerpo negro, el máximo de emisión por unidad de longitud de onda se encuentra en
> $$
> \lambda_{\max}T=b_{\mathrm W},\qquad b_{\mathrm W}\approx2{,}897\times10^{-3}\ \mathrm{m\,K}=2897\ \mu\mathrm{m\,K}.
> $$
> Al subir $T$, el máximo se desplaza hacia una $\lambda_{\max}$ menor. Esta relación permite estimar la región del espectro donde emite con más intensidad un cuerpo. [1](<Cap2_Teoria_29_10_2024.pdf>) (p. 5, ec. 2.3); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 5–7).

Para el Sol, una temperatura fotosférica cercana a 5800 K da $\lambda_{\max}\approx0{,}50\ \mu\mathrm m$, dentro de la luz visible. Para la temperatura efectiva terrestre de 255 K, el máximo es

$$
\lambda_{\max}=\frac{2897\ \mu\mathrm{m\,K}}{255\ \mathrm K}\approx11{,}4\ \mu\mathrm m.
$$

Así se entiende por qué la atmósfera interactúa con dos zonas espectrales distintas: la mayor parte de la radiación solar entrante es de onda corta y la emisión térmica terrestre es de onda larga. La atmósfera no tiene una transparencia única para ambas. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 5, 8–9); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 6–7, 17).

```anki
id: null
deck: Física::Terra, Ambiente e Clima::Balance radiativo
tags:
  - fisica
  - clima
  - radiacion
---
> [!note] Pregunta
> ¿Por qué aparece $S/4$ en el balance solar medio de una Tierra esférica?
===
> [!important] Respuesta
> La Tierra intercepta luz en un disco de área $\pi R^2$ y se promedia sobre una esfera de área $4\pi R^2$.
```

## Del Sol a la temperatura efectiva

### Luminosidad solar y distancia

> [!definicion] Luminosidad y constante solar
> La **luminosidad** $L_\odot$ es la energía que el Sol emite por unidad de tiempo, en vatios. A una distancia $d$, esa energía se reparte sobre una esfera de área $4\pi d^2$. La irradiancia solar perpendicular a los rayos es, por tanto,
> $$
> S(d)=\frac{L_\odot}{4\pi d^2}.
> $$
> La **constante solar** $S_0$ es la irradiancia media a la distancia media entre la Tierra y el Sol. Su valor depende de la precisión de la estimación y de la distancia orbital usada. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 5–6); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 8).

Con la distancia redondeada de $1{,}5\times10^{11}\ \mathrm m$, el cálculo del capítulo da $1379\ \mathrm{W\,m^{-2}}$; también cita $1367\ \mathrm{W\,m^{-2}}$ como valor más preciso. Las diapositivas de 2025/26 añaden $1361\ \mathrm{W\,m^{-2}}$ como una estimación aún más precisa. En los cálculos que siguen se usa $1361\ \mathrm{W\,m^{-2}}$ cuando se busca un valor de referencia actualizado por el material docente; los valores anteriores se conservan aquí como contexto histórico de las fuentes, no como tres cantidades simultáneas. [1](<Cap2_Teoria_29_10_2024.pdf>) (p. 6); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 8).

La luminosidad solar que da el capítulo es aproximadamente $3{,}9\times10^{26}\ \mathrm W$. La mayor parte de la radiación visible e infrarroja procede de la **fotosfera**, una capa de unos 300 km de espesor cuya temperatura, según el perfil del PDF, desciende aproximadamente desde 10 000 K en la base hasta 5000 K en la parte superior. Por encima se extiende la **cromosfera**, de unos 15 000 km de espesor: la fuente sitúa su temperatura desde unos 5000 K en la base hasta 500 000 K en la parte superior. La **corona** se diluye gradualmente en el espacio interplanetario y alcanza temperaturas medias de varios millones de kelvin. Estos valores describen el esquema docente; no son capas de temperatura uniforme. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 5–6).

La fotosfera explica bien la mayor parte del espectro visible e infrarrojo, pero no todo el espectro solar. Las longitudes de onda muy cortas y muy largas reciben una contribución importante de la cromosfera superior y de la corona. Aunque la intensidad solar total varía poco, el PDF destaca cambios mucho mayores en las bandas ultravioleta y de rayos X, relacionados con variaciones de densidad y temperatura en esas capas altas; esos flujos afectan a las partes superiores de las atmósferas planetarias. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 5–6).

La ley del inverso del cuadrado también permite comparar planetas. Si la distancia al Sol se multiplica por dos, la irradiancia se reduce a una cuarta parte. La tabla docente reúne distancias, flujos solares, albedos y temperaturas efectivas; el flujo está expresado en $\mathrm{kW\,m^{-2}}$ y la distancia en millones de kilómetros. Son cifras tabuladas en las fuentes, redondeadas para comparar tendencias.

| Planeta | Distancia al Sol (millones de km) | Flujo solar ($\mathrm{kW\,m^{-2}}$) | Albedo | $T_e$ (K) |
|---|---:|---:|---:|---:|
| Mercurio | 58 | 9,2 | 0,06 | 442 |
| Venus | 108 | 2,6 | 0,71 | 244 |
| Tierra | 150 | 1,38 | 0,33 | 255 |
| Marte | 228 | 0,60 | 0,17 | 216 |
| Júpiter | 778 | 0,049 | 0,73 | 87 |
| Saturno | 1430 | 0,015 | 0,76 | 63 |
| Urano | 2870 | 0,0037 | 0,93 | 33 |
| Neptuno | 4500 | 0,0015 | 0,84 | 32 |
| Plutón | 5900 | 0,00089 | 0,14 | 43 |

La tendencia principal es clara: los planetas más alejados reciben menos energía solar y suelen tener temperaturas efectivas menores. El albedo puede cambiar la comparación; Venus, por ejemplo, refleja una fracción grande de la radiación incidente y su temperatura efectiva resulta parecida a la terrestre pese a estar más cerca del Sol. El PDF contrasta esos 244 K efectivos con una temperatura superficial del orden de 700 K. La comparación ilustra la diferencia entre emisión planetaria y condiciones en superficie; el valor de 700 K es la aproximación redondeada que ofrece el material. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 6–8, tabla 2.2); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 12).

### Albedo y geometría del planeta

Un planeta intercepta radiación sobre su disco, de área $\pi R^2$, pero emite desde toda su superficie, de área $4\pi R^2$. Además, solo absorbe la fracción que no refleja.

> [!definicion] Albedo planetario
> El **albedo** $\alpha_p$ es la fracción de la radiación solar incidente que el sistema planeta–atmósfera devuelve al espacio. En el modelo simple, la fracción absorbida es $1-\alpha_p$. Con $0\leq\alpha_p\leq1$, un albedo mayor significa menos energía solar absorbida. [1](<Cap2_Teoria_29_10_2024.pdf>) (p. 6); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 9).

La potencia interceptada por un planeta de radio $R$ es

$$
P_{\mathrm{abs}}=\pi R^2S_0(1-\alpha_p).
$$

Si se supone que todo el planeta tiene una temperatura de emisión uniforme $T_e$ y emite como cuerpo negro, la potencia térmica emitida al espacio es

$$
P_{\mathrm{emit}}=4\pi R^2\sigma T_e^4.
$$

En equilibrio radiativo planetario, ambas potencias son iguales. Al cancelar $\pi R^2$ se obtiene

$$
\frac{(1-\alpha_p)S_0}{4}=\sigma T_e^4,
\qquad
T_e=\left(\frac{(1-\alpha_p)S_0}{4\sigma}\right)^{1/4}.
$$

El factor $1/4$ no es un ajuste empírico: sale de comparar el disco que intercepta la luz con la esfera sobre la que se promedia la energía. En unidades, $S_0/\sigma$ tiene dimensión $\mathrm K^4$, así que su raíz cuarta produce una temperatura absoluta. El radio desaparece; para este modelo, $T_e$ depende de la irradiancia y del albedo, no del tamaño del planeta. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 6–8, ecs. 2.4–2.7); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 9–12).

> [!definicion] Temperatura efectiva
> La **temperatura efectiva** $T_e$ es la temperatura que tendría un cuerpo negro que emitiera al espacio la misma potencia radiativa total que el planeta absorbe en equilibrio. Es una temperatura de emisión planetaria; no equivale necesariamente a la temperatura media de la superficie. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 7–8); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 10–12).

Con $S_0=1361\ \mathrm{W\,m^{-2}}$ y un albedo simplificado de $0{,}30$,

$$
F_{\mathrm{abs}}=\frac{(1-0{,}30)(1361\ \mathrm{W\,m^{-2}})}{4}
\approx238{,}2\ \mathrm{W\,m^{-2}},
$$

$$
T_e=\left(\frac{238{,}2\ \mathrm{W\,m^{-2}}}{5{,}67\times10^{-8}\ \mathrm{W\,m^{-2}\,K^{-4}}}\right)^{1/4}
\approx254{,}7\ \mathrm K.
$$

El valor está cerca de 255 K. La temperatura media superficial que el capítulo emplea como comparación es aproximadamente 288 K: la superficie es más cálida que la temperatura efectiva de emisión al espacio. La diferencia, unos 33 K, resume el efecto de la atmósfera en el intercambio radiativo. No demuestra por sí sola un mecanismo concreto; para explicarla hay que considerar cómo absorben y emiten la atmósfera y las nubes. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 7–8); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 10–12).

## Absorción espectral y efecto invernadero

### La ventana atmosférica

La atmósfera no absorbe todas las longitudes de onda por igual. En términos generales, deja pasar buena parte de la radiación visible y absorbe con intensidad varias bandas infrarrojas. El vapor de agua es un absorbente importante; también lo son el dióxido de carbono, el ozono, el metano y otros gases minoritarios.

La figura docente pone juntas tres cosas: el espectro solar, el espectro térmico de la Tierra y la fracción absorbida o dispersada por la atmósfera en cada longitud de onda. En el visible, gran parte de la radiación solar alcanza el suelo. En el infrarrojo, aparecen bandas de absorción asociadas a distintos gases. Entre aproximadamente 8 y 15 micrómetros hay una región de transmisión relativamente alta, llamada **ventana atmosférica**. No es un hueco perfectamente transparente: nubes y otros constituyentes pueden reducir la transmisión. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 8–9, fig. 2.5); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 17).

Como $T_e\approx255\ \mathrm K$ corresponde a un máximo de emisión cercano a $11{,}4\ \mu\mathrm m$, el máximo cae dentro de esa ventana aproximada, aunque la emisión real ocupa un intervalo amplio. La figura ayuda a explicar por qué el espectro observado desde el espacio no es idéntico a la radiación que emite la superficie: algunas bandas se absorben y se vuelven a emitir desde niveles atmosféricos más fríos. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 8–9, figs. 2.5–2.6).

### Gases de efecto invernadero y nubes

> [!definicion] Gas de efecto invernadero
> Un **gas de efecto invernadero** absorbe radiación infrarroja en determinadas bandas y puede emitir radiación infrarroja según su estado térmico. Así modifica la ruta por la que la energía superficial escapa al espacio. La absorción transfiere energía a los movimientos internos de la molécula; las colisiones redistribuyen esa energía en el aire y la emisión puede dirigirse tanto hacia arriba como hacia abajo. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 10–13); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 18, 28–29).

El dióxido de carbono tiene modos de vibración que absorben cerca de 15 micrómetros, banda que coincide con parte de la emisión terrestre. El metano, el óxido nitroso, los clorofluorocarbonos y el ozono también absorben radiación infrarroja en bandas propias. El PDF estima que, a igual cantidad y en un horizonte de 20 años, el efecto radiativo directo del metano es 72 veces el del dióxido de carbono. Sus efectos dependen de la absorción espectral, concentración, distribución y tiempo de permanencia; una comparación por molécula no equivale a comparar su efecto total en la atmósfera. El metano absorbe más por molécula que el dióxido de carbono en la comparación temporal que cita el capítulo, pero su concentración es mucho menor. Como ruta de eliminación, el PDF escribe la reacción $\mathrm{CH_4+OH\rightarrow CH_3+H_2O}$. El ozono se encuentra sobre todo entre unos 15 y 35 km según el texto: reducir el ozono estratosférico debilita la protección ultravioleta, mientras que el aumento de ozono en la baja atmósfera constituye contaminación. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 10–13, fig. 2.7); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 18–24).

El capítulo describe el origen y el destino de los principales gases:

| Gas | Fuentes o procesos descritos en el material | Observación física |
|---|---|---|
| $\mathrm{CO_2}$ | Combustión, respiración, procesos del suelo y liberación geológica; intercambio con océanos y vegetación | Su banda cercana a $15\ \mu\mathrm m$ coincide con emisión terrestre; su ajuste atmosférico involucra varios reservorios |
| $\mathrm{CH_4}$ | Humedales, arrozales, digestión animal y extracción de combustibles | El capítulo cita oxidación por radicales hidroxilo como sumidero y una permanencia media del orden de una década |
| CFC | Entre los compuestos que enumera el capítulo están CFCl$_3$ (F11) y CF$_2$Cl$_2$ (F12); usos históricos en refrigeración y aerosoles | El PDF cita una concentración total de $0{,}00000002\ \%$ en volumen y una permanencia superior a 50 años; cifras históricas de la fuente |
| $\mathrm{N_2O}$ | Procesos del suelo y océano, fertilizantes, combustión y cambios de uso del suelo | El material cita destrucción fotoquímica estratosférica y permanencias de varias décadas |
| $\mathrm{O_3}$ | Formación por acción de radiación ultravioleta sobre oxígeno; destrucción por reacciones químicas | El ozono estratosférico absorbe UV; el ozono troposférico también es contaminante |
| $\mathrm{H_2O}$ | Evaporación y evapotranspiración; condensación y precipitación | Es muy variable y participa en el transporte de calor latente |

Las concentraciones y tiempos numéricos del PDF se refieren a literatura y estimaciones anteriores a 2014, y algunos no se pueden reducir a una única vida atmosférica. Como cifras del texto, el dióxido de carbono se sitúa entre 260 y 280 ppm desde comienzos del Holoceno hasta la industrialización y alrededor de 400 ppm en 2014; el metano pasa de menos de 700 ppb antes de la industrialización a más de 1800 ppb, un aumento descrito como superior al 150 %. El PDF atribuye al metano una permanencia aproximada de 10 años, a los CFC más de 50 años y al óxido nitroso entre 55 y 116 años. Son valores históricos citados por el material, no datos actuales. Por ejemplo, el material presenta para $\mathrm{CO_2}$ tanto un tiempo de ajuste de 50–200 años como una permanencia que puede extenderse miles de años para una fracción de las emisiones. Son escalas distintas: el intercambio con océanos y biosfera elimina parte de un pulso, mientras que otra parte persiste mucho más tiempo. El PDF estima que más de la mitad de una emisión se retira en un siglo y que cerca del 20 % puede permanecer durante muchos milenios. No deben leerse como una única constante de vida ni como valores actuales. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 10–13); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 18–29).

El vapor de agua ocupa un lugar particular. El material lo identifica como el contribuyente más abundante al efecto invernadero natural, pero su cantidad atmosférica varía mucho y su permanencia media es breve, del orden de 10 días. Las proporciones que cita para su contribución son 36–66 % con cielo despejado y 66–85 % al incluir las nubes; dependen del método y de las condiciones atmosféricas, por lo que aquí se conservan como estimaciones de la fuente, no como porcentajes fijos. Cuando otro forzamiento calienta el aire, puede aumentar la cantidad de vapor que este contiene; como el vapor también absorbe infrarrojo, amplifica parte del calentamiento inicial. En esa relación, el vapor de agua actúa principalmente como **realimentación**, no como el forzamiento inicial persistente que aparece en la explicación del capítulo. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 12–13); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 25–26).

Las nubes no son gases, pero absorben y emiten infrarrojo; además reflejan radiación solar. Por eso su efecto no tiene un único signo: la reflexión tiende a reducir energía solar absorbida, mientras que la absorción y emisión infrarroja modifican la pérdida de calor. Nitrógeno, oxígeno y argón no se consideran gases de efecto invernadero principales porque sus moléculas homonucleares o monoatómicas no presentan el cambio de momento dipolar vibracional que permite una absorción infrarroja significativa. El PDF menciona moléculas como CO y HCl como absorbentes, pero de contribución menor por su baja abundancia y reactividad. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 12–13); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 27–29).

### Forzamiento radiativo

> [!definicion] Forzamiento radiativo
> El **forzamiento radiativo** expresa un cambio impuesto al balance de energía radiativa del sistema climático, medido como flujo por unidad de superficie, en $\mathrm{W\,m^{-2}}$. En la convención usada por el material, un forzamiento positivo favorece el calentamiento y uno negativo favorece el enfriamiento. La respuesta de la temperatura puede retrasarse mientras el sistema acumula o redistribuye energía. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 13–14, fig. 2.9); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 19–24, 59).

Las figuras de forzamiento reproducidas en el PDF proceden de informes IPCC antiguos, en particular de 2007; las diapositivas comparan gráficos de 2001, 2007, 2014 y 2021. En los gráficos se muestran barras de incertidumbre y una evolución temporal de la contribución de gases. El rango de error es especialmente amplio para aerosoles. Las cifras históricas de esas figuras sirven para interpretar el concepto y la incertidumbre; no son una tabla de valores actuales. [1](<Cap2_Teoria_29_10_2024.pdf>) (p. 14, fig. 2.9); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 19–24, 59).

## El presupuesto energético de la Tierra

### Un ejemplo con cien unidades

Para leer el diagrama docente, imagina que el flujo solar medio entrante vale 100 unidades. Las unidades son arbitrarias: sirven para seguir la energía, no corresponden a $100\ \mathrm{W\,m^{-2}}$.

| Trayecto de onda corta | Unidades |
|---|---:|
| Radiación solar entrante | 100 |
| Reflejada al espacio por la atmósfera y las nubes | 26 |
| Reflejada al espacio por la superficie | 7 |
| Absorbida por la atmósfera | 22 |
| Absorbida por el suelo | 45 |

Así, 33 unidades vuelven al espacio por reflexión y 67 son absorbidas en el sistema Tierra: 22 por la atmósfera y 45 por la superficie. El balance radiativo en el techo de la atmósfera (TOA) se cierra si el planeta emite 67 unidades de radiación térmica al espacio:

$$
100-(26+7)-67=0.
$$

En el desglose dibujado, 47 unidades se dispersan en las nubes: 26 vuelven al espacio y 21 se reenvían hacia el suelo. Otras 31 llegan directamente a la superficie; de estas, 24 se absorben y 7 se reflejan. Así, la superficie absorbe $21+24=45$ unidades y refleja otras 7. Junto con las 26 reflejadas por la atmósfera y las nubes, la reflexión total es 33. La atmósfera absorbe las 22 restantes. En el intercambio infrarrojo del esquema, el suelo emite 113 unidades; la atmósfera devuelve 98 hacia la superficie. El suelo absorbe además 45 unidades solares. Su presupuesto queda

$$
45+98=113+30.
$$

La superficie recibe 143 unidades y pierde 113 por radiación infrarroja y 30 por vías no radiativas. Esas 30 unidades representan sobre todo calor latente asociado a evaporación y, en menor medida, calor sensible transferido por convección. El suelo no está en equilibrio radiativo por sí solo, aunque el sistema global sí cierra su balance en el modelo. La imagen muestra flechas para distinguir la radiación solar, la emisión infrarroja y el flujo no radiativo; leer los números como una sola suma sin seguir su destino confunde los balances de superficie y planeta. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 9–10, fig. 2.6); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 30).

El efecto invernadero es el aumento de la temperatura superficial que resulta de la absorción y emisión atmosférica de radiación infrarroja. La expresión histórica funciona como imagen, pero una estufa real también limita el movimiento del aire mediante sus paredes; la atmósfera no es una cubierta sólida. Por eso el mecanismo físico relevante aquí es radiativo, acompañado en la atmósfera real por convección y cambios de fase del agua. [1](<Cap2_Teoria_29_10_2024.pdf>) (p. 10); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 27, 30).

## Modelos radiativos de capas atmosféricas

Los modelos de capas sustituyen la atmósfera continua por una o dos capas uniformes. Son ejercicios de contabilidad de flujos. En todos, $F$ representa la radiación solar global media absorbida por unidad de superficie, en $\mathrm{W\,m^{-2}}$; $T_s$ es la temperatura superficial; y la emisión de cada cuerpo negro es $\sigma T^4$. La energía solar se supone transparente a las capas y la radiación infrarroja se trata según la opacidad asignada. El modelo no incluye transporte convectivo, calor latente ni variación espectral detallada.

### Una capa completamente opaca al infrarrojo

> [!definicion] Modelo de una capa opaca
> El modelo de una capa opaca supone una superficie que absorbe radiación terrestre como cuerpo negro y una capa atmosférica transparente a la radiación solar, pero que absorbe toda la radiación infrarroja emitida por la superficie. La capa emite como cuerpo negro hacia arriba y hacia abajo, con la misma temperatura $T_a$. La radiación que escapa al espacio procede de la capa. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 14–15, fig. 2.10); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 31–34).

El equilibrio en el techo de la atmósfera exige que el flujo solar absorbido iguale la emisión ascendente de la capa:

$$
F=\frac{(1-\alpha_p)S_0}{4}=\sigma T_a^4=\sigma T_e^4.
$$

Por tanto, $T_a=T_e$. La capa absorbe la emisión infrarroja superficial $\sigma T_s^4$ y emite la misma cantidad hacia cada lado. Su balance es

$$
\sigma T_s^4=2\sigma T_a^4=2F.
$$

En la superficie también debe cumplirse el balance: recibe $F$ de radiación solar y $F$ de infrarrojo descendente, y emite $2F$. De aquí,

$$
T_s=2^{1/4}T_e\approx1{,}19T_e.
$$

Si $T_e=255\ \mathrm K$, el modelo da $T_s\approx303\ \mathrm K$. El resultado supera los 288 K que el capítulo atribuye a la temperatura media superficial observada. La diferencia indica las limitaciones del modelo: supone absorción infrarroja total, ignora que parte de la radiación escapa por la ventana atmosférica, omite que la atmósfera y las nubes absorben radiación solar y no permite que la superficie pierda energía por evaporación o calor sensible. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 14–15, ecs. 2.9–2.11); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 31–34).

### Dos capas completamente opacas

> [!definicion] Modelo de dos capas opacas
> Se divide la atmósfera en una capa inferior de temperatura $T_1$ y otra superior de temperatura $T_2$. Ambas son transparentes a la radiación solar, opacas al infrarrojo y emiten como cuerpos negros hacia arriba y hacia abajo. En equilibrio, la capa superior emite al espacio el flujo $F$. [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 35–36).

El balance de la capa superior da $\sigma T_2^4=F$, porque su emisión ascendente es la que sale al espacio. Por tanto, $T_2=T_e$. La capa inferior tiene $\sigma T_1^4=2F$, así que $T_1=2^{1/4}T_e$. Emite $2F$ hacia arriba y $2F$ hacia abajo. Absorbe $3F$ desde la superficie y $F$ que recibe desde arriba, de modo que su emisión total, $4F$, cierra su balance. La superficie absorbe el flujo solar $F$ y el infrarrojo descendente de la capa inferior, $2F$. Por tanto, la superficie tiene $T_s^4=3T_e^4$ y las temperaturas satisfacen $T_s>T_1>T_2=T_e$. Su balance es

$$
\sigma T_s^4=F+2F=3F,
\qquad
T_s=3^{1/4}T_e.
$$

Al aumentar el número de capas opacas, aumenta la temperatura superficial que necesita el modelo para que el flujo que escapa al espacio siga siendo $F$. Es una consecuencia de las hipótesis de capas negras y equilibrio radiativo, no una regla para convertir una concentración de gas en una temperatura real. [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 35–36).

### Una capa parcialmente opaca al infrarrojo

El modelo parcial conserva la atmósfera transparente a la radiación solar, pero deja que una fracción del infrarrojo superficial atraviese la capa. Sea $a$ la absorptividad infrarroja, con $0\leq a\leq1$, y sea $\varepsilon=a$ la emisividad de la capa, como supone el modelo docente. La fracción transmitida es $1-a$. La superficie tiene temperatura $T_s$ y la capa, $T_a$.

> [!definicion] Modelo de una capa parcialmente opaca
> En este modelo, la radiación infrarroja que llega al techo de la atmósfera es la suma de la parte superficial transmitida, $(1-a)\sigma T_s^4$, y la emisión ascendente de la capa, $a\sigma T_a^4$. La capa absorbe $a\sigma T_s^4$ desde la superficie y emite $a\sigma T_a^4$ en cada dirección. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 15–17, fig. 2.11, ecs. 2.12–2.15); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 37–39).

El balance de la capa es

$$
a\sigma T_s^4=2a\sigma T_a^4.
$$

Para $a>0$ podemos dividir por $a\sigma$ y obtener $T_s^4=2T_a^4$. El balance en la superficie y el balance de salida TOA son, respectivamente,

$$
F+a\sigma T_a^4=\sigma T_s^4,
\qquad
F=(1-a)\sigma T_s^4+a\sigma T_a^4.
$$

Usando $F=\sigma T_e^4$ y la relación $T_s^4=2T_a^4$,

$$
(2-a)\sigma T_a^4=F,
\qquad
T_a=\left(\frac{1}{2-a}\right)^{1/4}T_e,
\qquad
T_s=\left(\frac{2}{2-a}\right)^{1/4}T_e.
$$

Para $T_e=255\ \mathrm K$ y $a=0{,}8$, el modelo da $T_a\approx244\ \mathrm K$ y $T_s\approx290\ \mathrm K$. Para $a=0{,}9$, da aproximadamente $T_a\approx249\ \mathrm K$ y $T_s\approx296\ \mathrm K$, en concordancia con las diapositivas. Cuando $a=1$, se recupera el modelo totalmente opaco: $T_s=2^{1/4}T_e$. [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 38–39).

El límite $a=0$ requiere cuidado. La fórmula superficial sí tiende a $T_s=T_e$, pues no hay absorción infrarroja atmosférica. Pero el balance de la capa se convierte en $0=0$: una capa transparente no intercambia radiación y su temperatura $T_a$ queda indeterminada por este modelo. La expresión algebraica para $T_a$ al tomar el límite $a\to0^+$ no describe una temperatura física determinada en $a=0$. Esta salvedad corrige la lectura literal de la diapositiva 39. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 15–17); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 37–39).

## Aerosoles y radiación

### Qué es un aerosol y de dónde procede

> [!definicion] Aerosol
> Un **aerosol** es un conjunto de partículas sólidas o gotas líquidas suspendidas en un gas. Su composición, tamaño, forma y altura condicionan cuánto tiempo permanece en el aire, dónde se deposita y cómo interactúa con radiación y nubes. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 17–18); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 40–48).

Los aerosoles pueden ser **primarios**, si se emiten directamente como partículas —por ejemplo, polvo levantado por erosión, sal marina o ceniza volcánica—, o **secundarios**, si se forman en la atmósfera a partir de gases mediante nucleación y crecimiento. El material distingue cuatro grupos por aspecto y tamaño aproximado:

| Grupo descrito en el curso | Estado y tamaño aproximado | Ejemplos del material |
|---|---|---|
| Emisiones y humos | Partículas sólidas finas; el texto cita desde 0,001 hasta 1 $\mu\mathrm m$ para emisiones y humos habitualmente menores de 10 $\mu\mathrm m$ | Combustión incompleta de carbón, petróleo o gas |
| Polvo | Partículas sólidas, aproximadamente 1–100 $\mu\mathrm m$ | Suelo, arena, fertilizantes, carbón, cemento y polen |
| Névoas o nieblas | Gotas líquidas menores de 10 $\mu\mathrm m$ | Gotas de agua; cuando reducen la visibilidad forman niebla |
| Sprays | Gotas líquidas mayores de 10 $\mu\mathrm m$ | Salpicadura marina o producción humana |

Los límites se solapan y las etiquetas del material responden a una clasificación didáctica, no a fronteras universales. Las diapositivas y el PDF también presentan mapas de espesor óptico de aerosoles medidos por satélite y un ejemplo de pluma de polvo transportada en altura. Esos casos muestran que la cantidad y elevación de partículas varían espacialmente; no permiten deducir por sí solos una emisión o un efecto climático numérico. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 17–18, tabla 2.3); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 40–47).

El PDF atribuye cerca de tres cuartas partes de los aerosoles a fuentes naturales, como sal marina, suelo, rocas, volcanes, incendios y reacciones químicas; el resto, a fuentes humanas. Esa proporción depende del tamaño de partícula incluido, del lugar y del método de estimación. La tabla del capítulo atribuye a Raes et al. (2000) el siguiente inventario, en teragramos por año ($1\,\mathrm{Tg}=10^{12}\,\mathrm g$). Es una tabla de consulta para comparar grupos y órdenes de magnitud; al narrarla, conviene explicar su organización sin leer cada fila en voz alta:

| Grupo | Fracción o fuente como aparece en la tabla | Emisión (Tg/año) |
|---|---|---:|
| Aerosol marino | Total | 5900 |
| Aerosol marino | 0–2 $\mu\mathrm m$ | 82,1 |
| Aerosol marino | 2–20 $\mu\mathrm m$ | 2460 |
| Polvo del suelo | menor de 1 $\mu\mathrm m$ | 250 |
| Polvo del suelo | 1–10 $\mu\mathrm m$ | 1000 |
| Polvo del suelo | 0,2–2 $\mu\mathrm m$ | 250 |
| Polvo del suelo | 2–20 $\mu\mathrm m$ | 4875 |
| Carbono orgánico | Total | 69 |
| Carbono orgánico | Quema de biomasa | 54,3 |
| Carbono orgánico | Combustibles fósiles | 28,8 |
| Carbono orgánico | Oxidación de terpenos | 18,5 |
| Carbono elemental | Total | 12 |
| Carbono elemental | Quema de biomasa | 5,6 |
| Carbono elemental | Combustibles fósiles | 6,6 |
| Sulfato (como $\mathrm{H_2SO_4}$) | Total | 150 |
| Sulfato (como $\mathrm{H_2SO_4}$) | Natural | 32 |
| Sulfato (como $\mathrm{H_2SO_4}$) | Antropogénico | 111 |
| Nitrato | Total | 11,3 |
| Amonio | Total | 33,6 |

Varios renglones no cierran aritméticamente: por ejemplo, las emisiones por tamaño de polvo superan el total general, y las fuentes de carbono orgánico superan el subtotal indicado. El total de aerosol marino tampoco concuerda con los dos intervalos de tamaño que se listan. Se reproduce la tabla para preservar el registro docente y se señalan estas incoherencias; sus números no deben emplearse en cálculos ni como inventario actual. [1](<Cap2_Teoria_29_10_2024.pdf>) (p. 18, tabla 2.3).

El tiempo de residencia atmosférico típico citado es de unos días a una semana. Durante ese tiempo las partículas pueden coagularse, condensar material, evaporarse o reaccionar químicamente dentro de las nubes. La deposición seca ocurre por sedimentación y difusión; la deposición húmeda, por precipitación. Como muchas partículas se eliminan pronto, sus efectos suelen ser más intensos cerca de las fuentes, aunque algunas plumas pueden transportarse lejos y en altura. [1](<Cap2_Teoria_29_10_2024.pdf>) (p. 18); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 48).

### Tamaño de partícula y dispersión

La interacción de la luz con una partícula depende de la relación entre su radio $r$ y la longitud de onda incidente $\lambda$. Para una partícula aproximadamente esférica se define el parámetro adimensional

$$
x=\frac{2\pi r}{\lambda}.
$$

El factor $2\pi r$ compara la circunferencia de la partícula con una longitud de onda. En la gráfica del curso, los ejes son logarítmicos: al desplazarse en diagonal se mantiene aproximadamente constante el valor de $x$. Se distinguen tres regímenes:

| Régimen | Relación orientativa | Interacción y ejemplo |
|---|---|---|
| Rayleigh | $r\ll\lambda$ ($x\ll1$) | Dispersión por moléculas y partículas muy pequeñas; favorece longitudes de onda cortas |
| Mie | $r\sim\lambda$ ($x$ del orden de 1) | Dispersión por aerosoles de tamaño comparable a la longitud de onda; suele ser más intensa hacia delante |
| Óptica geométrica | $r\gg\lambda$ ($x\gg1$; el esquema sitúa el dominio claro por encima de decenas) | Reflexión y refracción, como aproximación para partículas mucho mayores que la onda |

El régimen de Rayleigh produce una intensidad dispersada que, en las condiciones del modelo, varía aproximadamente como $\lambda^{-4}$. Para comparar luz azul de 490 nm con luz roja de 700 nm,

$$
\frac{I_{490}}{I_{700}}\approx\left(\frac{700}{490}\right)^4\approx4{,}16.
$$

El texto y las diapositivas dan 9,4 para esa comparación; esa cifra no se obtiene de la relación $\lambda^{-4}$ con 490 nm y 700 nm. Debe leerse como una errata aritmética del material. La dependencia cualitativa sí explica que la luz azul se disperse más que la roja y que el cielo se vea azul. Cerca del Sol, la luz que llega directamente ha perdido parte de las longitudes cortas por dispersión, de modo que el disco solar y el cielo próximo pueden verse rojizos; sin atmósfera, el cielo aparecería negro. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 19–20, ecs. 2.16 y fig. 2.13); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 49–57).

El PDF llama «ley de Rayleigh–Jeans» a la dependencia $\lambda^{-4}$. Esa denominación es incorrecta: se trata de la dispersión de Rayleigh; la ley de Rayleigh–Jeans nombra una aproximación clásica al espectro de radiación de cuerpo negro. Se mantiene aquí el resultado físico con su nombre correcto. [3](https://farside.ph.utexas.edu/teaching/jk1/lectures/node108.html); [4](https://openstax.org/books/university-physics-volume-3/pages/6-1-blackbody-radiation).

Cuando $r$ es comparable a $\lambda$, el régimen de Mie describe la dispersión por partículas esféricas de tamaño mayor. Las gotas de nube del orden de decenas de micrómetros dispersan todos los colores visibles de forma relativamente parecida, y por eso las nubes suelen verse blancas. En una nube más gruesa, menos luz atraviesa el conjunto y su base puede verse oscura. Para partículas mucho mayores que la longitud de onda, la descripción mediante rayos de la óptica geométrica resulta útil. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 19–20, fig. 2.12); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 53–57).

### Efecto radiativo directo e indirecto

Un aerosol puede dispersar radiación, absorberla o hacer ambas cosas. La dispersión solar hacia el espacio reduce la energía que llega a la superficie y tiende a enfriar. La absorción, en cambio, calienta la partícula y el aire circundante; según la altura y las propiedades de la superficie, puede cambiar también el balance regional. Por eso no todos los aerosoles tienen el mismo signo.

> [!definicion] Efecto directo e indirecto de los aerosoles
> El **efecto directo** surge de la dispersión o absorción de radiación por las propias partículas. El **efecto indirecto** aparece cuando cambian las propiedades de las nubes, por ejemplo porque las partículas actúan como núcleos de condensación y alteran el número y tamaño de las gotas. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 18, 20); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 58–59).

El capítulo explica que, con pocos núcleos de condensación, las gotas disponibles pueden crecer con rapidez; con muchos núcleos compitiendo por el vapor, las gotas tienden a crecer más despacio y la precipitación puede retrasarse. Es una descripción de mecanismo, no una regla suficiente para predecir la lluvia: también importan la dinámica de la nube y las condiciones ambientales. El PDF cita albedo inferior al 40 % para nubes poco espesas (menos de unos 50 m) y de hasta 80 % para nubes de más de 5000 m. Son órdenes de magnitud ilustrativos de esa fuente: la reflectividad depende también del tipo de nube, la composición y la geometría de iluminación. [1](<Cap2_Teoria_29_10_2024.pdf>) (p. 18).

Como cifras históricas, el PDF y las diapositivas citan un efecto directo de aproximadamente $-0{,}5\ \mathrm{W\,m^{-2}}$ y uno indirecto de $-0{,}7\ \mathrm{W\,m^{-2}}$, sumados en la fuente como $-1{,}2\ \mathrm{W\,m^{-2}}$. El texto los describe como reducción del flujo que alcanza la superficie, mientras que las figuras tituladas *Radiative Forcing* muestran estimaciones de forzamiento en el balance planetario. No son magnitudes intercambiables sin más: se conserva el carácter y el contexto de la cifra del texto, y se evita presentarla como una estimación contemporánea del forzamiento global. Las barras de error de aerosoles en los gráficos docentes son además amplias. [1](<Cap2_Teoria_29_10_2024.pdf>) (pp. 14, 20, fig. 2.9); [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 58–59).

## Condiciones de validez, límites y errores frecuentes

Los cálculos de temperatura efectiva suponen equilibrio radiativo, albedo y flujo solar fijados, emisión térmica como cuerpo negro y una temperatura efectiva uniforme. El promedio $S_0/4$ corresponde a una esfera iluminada por un haz aproximadamente paralelo; no describe la irradiancia local, que depende de la hora y el ángulo solar. Las temperaturas de capas requieren las hipótesis específicas de opacidad y equilibrio de cada modelo; al cambiar esas hipótesis cambian las ecuaciones y el resultado.

Un error frecuente consiste en llamar temperatura efectiva a la temperatura superficial: la primera caracteriza la potencia que escapa al espacio. Otro es sumar los flujos de superficie como si fueran el balance TOA; en el presupuesto de 100 unidades, el suelo recibe energía y la atmósfera la redistribuye antes de que salga al espacio. En el modelo parcial, dividir el balance atmosférico por $a$ solo es válido para $a>0$. En la dispersión, la ley $I\propto\lambda^{-4}$ permite comparar longitudes de onda bajo las condiciones de Rayleigh; no describe partículas de cualquier tamaño.

## Práctica guiada: aplicación docente de un planeta con una capa atmosférica

Las diapositivas proponen calcular los flujos y temperaturas para un planeta idealizado con constante solar $S_0=1360\ \mathrm{W\,m^{-2}}$ y albedo $\alpha_p=0{,}3$. Se resuelve primero el balance sin atmósfera y luego se usa la misma temperatura efectiva para comparar los modelos de capas. [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 32, 36).

#### Ejercicio de aplicación propuesto en las diapositivas — emisión y temperatura superficial

**Datos.** $S_0=1360\ \mathrm{W\,m^{-2}}$, $\alpha_p=0{,}3$ y $\sigma=5{,}67\times10^{-8}\ \mathrm{W\,m^{-2}\,K^{-4}}$. Se buscan el flujo medio absorbido y la temperatura efectiva; después, la temperatura superficial de los modelos de una y dos capas.

**Desarrollo.** Primero se promedia la radiación interceptada sobre la superficie esférica y se descuenta la reflexión:

$$
F=\frac{(1-\alpha_p)S_0}{4}
=\frac{0{,}7\times1360\ \mathrm{W\,m^{-2}}}{4}
=238\ \mathrm{W\,m^{-2}}.
$$

El equilibrio en el techo de la atmósfera fija la temperatura efectiva:

$$
T_e=\left(\frac{F}{\sigma}\right)^{1/4}
=\left(\frac{238}{5{,}67\times10^{-8}}\right)^{1/4}\mathrm K
\approx255\ \mathrm K.
$$

En el modelo de una capa totalmente opaca, la capa está a $T_a=T_e$ y la superficie cumple $\sigma T_s^4=2F$. Por tanto, $T_s=2^{1/4}T_e\approx303\ \mathrm K$. En el modelo de dos capas totalmente opacas, la superficie cumple $\sigma T_s^4=3F$, de modo que $T_s=3^{1/4}T_e\approx335\ \mathrm K$. Esos resultados ilustran cómo el número de capas cambia la temperatura requerida para mantener la misma emisión al espacio; no son una predicción de temperatura para la Tierra. [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 31–36).

Para la capa parcialmente opaca, las diapositivas dan dos comprobaciones adicionales: con $a=0{,}8$, $T_a=244\ \mathrm K$ y $T_s=290\ \mathrm K$; con $a=0{,}9$, $T_a=249\ \mathrm K$ y $T_s=296\ \mathrm K$. Las expresiones derivadas reproducen esos valores al tomar $T_e\approx255\ \mathrm K$. [2](<Cap2_Slides_30_11_2025.pptx>) (diap. 37–39).

> [!resolucion] Comprobación del balance
> En el caso de $a=0{,}8$, el balance de superficie exige $F+0{,}8\sigma T_a^4=\sigma T_s^4$. Como $T_s^4=2T_a^4$, queda $F=1{,}2\sigma T_a^4$, es decir, $T_a=T_e/(1{,}2)^{1/4}\approx244\ \mathrm K$. La superficie resulta $T_s=2^{1/4}T_a\approx290\ \mathrm K$. La comprobación usa la misma hipótesis del modelo: una sola capa en equilibrio, con emisividad igual a absorptividad.

## Conexión con el capítulo siguiente

El balance radiativo establece cuánta energía entra y sale, pero no describe por sí solo cómo se reparte el calor entre latitudes, alturas y océanos. Ese transporte es el puente hacia la [[Física/Grado/1º/Terra, Ambiente e Clima/03 Circulación atmosférica y oceánica|circulación atmosférica y oceánica]].

## 📚 Fuentes

### Material base aportado

- [1. Ricardo Machado Trigo — *Terra, Ambiente e Clima*, capítulo 2, «Balanço Radiativo», 21 pp.](<Cap2_Teoria_29_10_2024.pdf>). Estructura vertical, composición, leyes radiativas, balance planetario, absorción atmosférica, gases de efecto invernadero, presupuesto de energía, modelos de una capa y aerosoles; se indican páginas y figuras junto a cada bloque. La versión editable del mismo texto, `Cap2_Teoria_29_10_2024.docx`, se consultó solo para aclarar la disposición de la tabla 2.3; es una copia redundante, no una fuente independiente.
- [2. Ricardo Machado Trigo — *Terra, Ambiente e Clima*, diapositivas del capítulo 2, curso 2025/26, 59 diap.](<Cap2_Slides_30_11_2025.pptx>). Espectro, constante solar, albedo, temperatura efectiva, forzamiento, presupuestos, modelos de capas y aerosoles; se indican diapositivas junto a cada bloque.

### Ampliación externa consultada

- [3. University of Texas at Austin — Rayleigh scattering](https://farside.ph.utexas.edu/teaching/jk1/lectures/node108.html). Dispersión de Rayleigh y dependencia con la longitud de onda.
- [4. OpenStax, *University Physics*, vol. 3, §6.1 — Blackbody Radiation](https://openstax.org/books/university-physics-volume-3/pages/6-1-blackbody-radiation). Espectro de Planck y ley de Rayleigh–Jeans como aproximación clásica de cuerpo negro.

### Procedencia histórica de cifras

Las concentraciones, estimaciones de emisiones y valores de forzamiento anteriores a 2014 se atribuyen al PDF o a las fuentes citadas dentro de ese material. La tabla de emisiones de aerosoles se atribuye en el capítulo a Raes et al. (2000); las figuras de forzamiento se identifican con informes IPCC de 2001, 2007, 2014 o 2021. Su mención registra la procedencia docente, no afirma que esos valores hayan sido actualizados en esta nota.

### Bibliografía citada por el material base

Las referencias siguientes aparecen en la bibliografía del PDF; se registran como procedencia de los apuntes, no como obras consultadas directamente para esta nota.

- Ahrens, C. Donald, *Meteorology Today: An Introduction to Weather, Climate and the Environment*, 8.ª ed., Thomson Brooks/Cole, 2007.
- Graedel, T. E. y P. J. Crutzen, *Atmospheric Change: An Earth System Perspective*, W. H. Freeman, 1993.
- Miranda, P., *Meteorologia e Ambiente*, Universidade Aberta, 2002.
- Wallace, J. M. y P. V. Hobbs, *Atmospheric Science: An Introductory Survey*, 2.ª ed., Academic Press, 2006.

## 🧑‍🏫 Prompt para tutor conversacional

Actúa como tutor universitario introductorio de *Terra, Ambiente e Clima*. Formula una pregunta cada vez y espera respuesta. Pide explicar por qué la atmósfera tiene capas térmicas; interpretar las leyes de Planck, Stefan–Boltzmann y Wien; derivar el factor geométrico $1/4$ y calcular una temperatura efectiva con unidades; leer la ventana atmosférica y distinguir absorción de emisión; cerrar el presupuesto de 100 unidades en TOA y superficie; reconstruir los balances de una capa opaca, dos capas y una capa parcialmente opaca; y clasificar aerosoles mediante $2\pi r/\lambda$. Si la respuesta confunde temperatura efectiva con temperatura superficial, flujo solar perpendicular con promedio global, una estimación antigua con una medida actual o dispersión de Rayleigh con la ley de Rayleigh–Jeans, ofrece primero una pista basada en el balance o en las unidades. Cierra cada ejercicio comprobando hipótesis y explicando qué parte del mecanismo queda fuera del modelo.
