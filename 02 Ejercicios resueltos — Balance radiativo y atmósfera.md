---
title: Ejercicios resueltos — Balance radiativo y atmósfera
aliases:
  - TAC — soluciones de la Série 2
asignatura: Terra, Ambiente e Clima
rama:
  - Física atmosférica
  - Climatología
tipo:
  - problemas
  - procedimiento
nivel: universitario-introductorio
estado: revisada
capa: curricular
fsrs_goal: Calcular la irradiancia y temperatura efectiva de planetas a partir de luminosidad, distancia y albedo; plantear y resolver balances radiativos de una y dos capas; explicar el papel de gases de efecto invernadero y aerosoles y clasificar partículas por su parámetro de tamaño, con unidades e hipótesis explícitas.
requiere:
  - "[[Física/Grado/1º/Terra, Ambiente e Clima/02 Balance radiativo y atmósfera|Balance radiativo y atmósfera]]"
tags:
  - fisica
  - clima
  - radiacion
  - atmosfera
  - ejercicios
  - fcul
  - curricular
---


# Ejercicios resueltos — Balance radiativo y atmósfera

La serie plantea catorce problemas sobre irradiancia solar, temperatura efectiva, modelos radiativos de capas, gases de efecto invernadero y aerosoles. Los enunciados se reproducen en portugués para conservar sus condiciones y notación; las resoluciones explican el método en castellano. El PDF disponible contiene los enunciados, no una clave oficial. Los resultados se obtienen con las constantes y datos impresos en la serie, y se contrastan con el capítulo teórico y las diapositivas cuando estos ofrecen una comparación. [1](<Serie_2.pdf>) (pp. 1–3); [2](<Cap2_Teoria_29_10_2024.pdf>); [3](<Cap2_Slides_30_11_2025.pptx>).

La nota de referencia desarrolla los conceptos y las hipótesis de los modelos: [[Física/Grado/1º/Terra, Ambiente e Clima/02 Balance radiativo y atmósfera|Balance radiativo y atmósfera]]. Aquí se mantienen a la vista los balances, sustituciones, unidades y comprobaciones propios de cada ejercicio.

## Datos comunes y convenciones

La serie proporciona $T_\odot=5800\ \mathrm K$, $R_\odot=6{,}96\times10^5\ \mathrm{km}$, $L_\odot=3{,}9\times10^{26}\ \mathrm W$, $\sigma=5{,}67\times10^{-8}\ \mathrm{W\,m^{-2}\,K^{-4}}$ y $1\ \mathrm{AU}=150\times10^6\ \mathrm{km}$. En los cálculos se pasan las distancias a metros. La temperatura efectiva se expresa en kelvin; una diferencia de temperaturas puede expresarse indistintamente en kelvin o grados Celsius. El radio solar no hace falta si se usa directamente la luminosidad dada. [1](<Serie_2.pdf>) (p. 1).

Para los ejercicios 1–6 se adopta el modelo de equilibrio radiativo planetario: el planeta intercepta la radiación sobre un disco, la absorbe según su albedo y emite como cuerpo negro sobre toda su superficie. Para ejercicios 7–9 se define $F=(1-\alpha_p)S_0/4$, el flujo solar global medio absorbido por unidad de área. El símbolo $\alpha_p$ designa siempre el **albedo planetario**. En el ejercicio 14, el enunciado usa otra letra para un parámetro de tamaño; allí se escribirá $\alpha_{\mathrm{size}}$ para evitar confundirlo con el albedo.

## Práctica graduada

Para resolver la serie sin mirar el desarrollo, empieza por los ejercicios **1–6**, que aplican luminosidad, distancia, albedo y temperatura efectiva. Continúa con **7–9**, donde la tarea principal es contabilizar flujos antes de despejar temperaturas. Termina con **10–14**, que piden explicar mecanismos, comparar categorías y calcular el parámetro de tamaño. En todos los casos, anota primero los datos, las incógnitas y las hipótesis.

## Soluciones razonadas

### Ejemplo trabajado: ejercicio 1 — Irradiancia a una distancia dada

> [!quote] Enunciado 1
> Determine a expressão geral da constante solar $S_d$ para um planeta que orbita em torno do Sol à distância média $d$.

#### Resolución

La luminosidad $L_\odot$ es la potencia total emitida por el Sol. Si la radiación se reparte isotrópicamente y no pierde energía en el trayecto, a distancia $d$ atraviesa una esfera de área $4\pi d^2$. Por tanto,

$$
S_d=\frac{L_\odot}{4\pi d^2}.
$$

Con $L_\odot$ en vatios y $d$ en metros, $S_d$ queda en $\mathrm{W\,m^{-2}}$. A una unidad astronómica, los datos de la serie dan

$$
S_{1\,\mathrm{AU}}=\frac{3{,}9\times10^{26}\ \mathrm W}{4\pi(1{,}50\times10^{11}\ \mathrm m)^2}
=1{,}379\times10^3\ \mathrm{W\,m^{-2}}.
$$

El resultado, aproximadamente $1379\ \mathrm{W\,m^{-2}}$, coincide con el cálculo histórico del capítulo para la distancia redondeada de 1 AU. Las diapositivas y el texto citan también estimaciones más precisas de $1361$–$1367\ \mathrm{W\,m^{-2}}$; no deben mezclarse con el cálculo que usa $L_\odot$ y $d$ redondeados de esta serie. [1](<Serie_2.pdf>) (p. 1); [2](<Cap2_Teoria_29_10_2024.pdf>) (p. 6); [3](<Cap2_Slides_30_11_2025.pptx>) (diap. 8).

### 2. Temperatura efectiva de un planeta

> [!quote] Enunciado 2
> Determine a expressão geral da temperatura de emissão para um planeta esférico (raio $r_p$) e com albedo $\alpha_p$. Desenhe o esquema geral e identifique os 3 principais pressupostos para obter a expressão geral.

#### Resolución

El planeta intercepta la potencia solar sobre su sección circular, de área $\pi r_p^2$. Solo absorbe la fracción $1-\alpha_p$. En equilibrio, esa potencia iguala la radiación térmica emitida por toda la esfera, de área $4\pi r_p^2$:

$$
P_{\mathrm{abs}}=\pi r_p^2S_d(1-\alpha_p),\qquad
P_{\mathrm{emit}}=4\pi r_p^2\sigma T_e^4.
$$

Igualamos, cancelamos el área común y despejamos la temperatura:

$$
\pi r_p^2S_d(1-\alpha_p)=4\pi r_p^2\sigma T_e^4,
\qquad
T_e=\left(\frac{S_d(1-\alpha_p)}{4\sigma}\right)^{1/4}.
$$

Al sustituir el resultado del ejercicio 1,

$$
T_e=\left(\frac{L_\odot(1-\alpha_p)}{16\pi\sigma d^2}\right)^{1/4}.
$$

La cancelación de $r_p$ muestra que el tamaño no afecta a $T_e$ en este modelo. También revela el factor geométrico $1/4$: la irradiancia interceptada sobre el disco se promedia sobre la superficie completa de la esfera.

El esquema que pide el enunciado puede trazarse como: Sol $\to$ flujo $S_d$ perpendicular a los rayos $\to$ disco planetario $\pi r_p^2$; una fracción $\alpha_p$ vuelve al espacio y la fracción restante se absorbe; el planeta emite infrarrojo desde $4\pi r_p^2$.

Los tres supuestos operativos son: **(1)** el flujo solar es aproximadamente paralelo y uniforme sobre el disco interceptado; **(2)** el planeta se representa mediante un albedo único, y emite como cuerpo negro con emisividad uno; **(3)** se alcanza equilibrio radiativo y se representa la emisión mediante una temperatura efectiva uniforme. El modelo omite transporte entre regiones, atmósfera y fuentes internas. Dimensionalmente, $S_d/\sigma$ tiene unidad $\mathrm K^4$, así que la raíz cuarta produce kelvin. La emisión térmica de cuerpo negro y sus leyes integrales se desarrollan también en OpenStax. [1](<Serie_2.pdf>) (p. 1); [2](<Cap2_Teoria_29_10_2024.pdf>) (pp. 6–8, ecs. 2.4–2.7); [3](<Cap2_Slides_30_11_2025.pptx>) (diap. 9–10); [4](https://openstax.org/books/university-physics-volume-3/pages/6-1-blackbody-radiation).

### 3. Temperaturas efectivas y temperaturas observadas

> [!quote] Enunciado 3
> Use os dados da Tabela para calcular a temperatura de emissão relativa aos planetas indicados. Compare os valores das temperaturas assim obtidas com as temperaturas médias observadas de facto à superfície e interprete os resultados tendo em conta a figura de baixo.

La tabla del boletín especifica distancias en millones de kilómetros, radios en kilómetros, albedos y temperaturas medias observadas en °C. Se reproduce el conjunto de datos utilizado:

| Planeta | Distancia (10$^6$ km) | Radio (km) | Albedo | Temperatura media observada (°C) |
|---|---:|---:|---:|---:|
| Tierra | 150 | 6370 | 0,30 | 15 |
| Venus | 108 | 6052 | 0,80 | 457 |
| Marte | 228 | 3397 | 0,22 | −55 |
| Júpiter | 778 | 69 500 | 0,34 | −149 |

#### Resolución

Para cada distancia se calcula $S_d=L_\odot/(4\pi d^2)$ y luego

$$
T_e=\left(\frac{(1-\alpha_p)S_d}{4\sigma}\right)^{1/4}.
$$

El radio aparece en las potencias interceptada y emitida, pero se cancela. Convertimos primero $10^6\ \mathrm{km}$ a metros y usamos $\sigma$ en unidades SI.

| Planeta | $d$ (m) | $S_d$ (W m$^{-2}$) | $\alpha_p$ | $T_e$ (K) | Temperatura media observada (K) |
|---|---:|---:|---:|---:|---:|
| Tierra | $1,50\times10^{11}$ | 1379,3 | 0,30 | 255,4 | 288,2 |
| Venus | $1,08\times10^{11}$ | 2660,8 | 0,80 | 220,1 | 730,2 |
| Marte | $2,28\times10^{11}$ | 597,0 | 0,22 | 212,9 | 218,2 |
| Júpiter | $7,78\times10^{11}$ | 51,27 | 0,34 | 110,5 | 124,2 |

La temperatura observada en kelvin se obtiene sumando 273,15 al dato Celsius. En la Tierra, $288{,}2-255{,}4\approx32{,}7\ \mathrm K$: la superficie media es más cálida que la temperatura efectiva de emisión. En Venus la diferencia asciende a unos $510\ \mathrm K$, mientras que en Marte ronda $5\ \mathrm K$. La figura del enunciado dibuja perfiles de Venus, Tierra y Marte; solo para esos tres planetas debe leerse el contraste entre temperatura superficial y temperatura efectiva: es grande en Venus, apreciable en la Tierra y mucho menor en Marte, cuya atmósfera es tenue. Júpiter aparece en la tabla, pero no en el esquema. Su temperatura observada de $124{,}2\ \mathrm K$ supera en unos $13{,}6\ \mathrm K$ la $T_e$ calculada. El enunciado no especifica el nivel de presión al que corresponde esa temperatura, y Júpiter no tiene una superficie sólida que pueda equipararse a las superficies de los planetas rocosos. NASA explica que los gigantes gaseosos se caracterizan mediante temperaturas de niveles atmosféricos definidos por presión; además, Júpiter emite calor interno. Por tanto, la diferencia numérica es una comparación entre los datos del ejercicio y el modelo solar simplificado, no una medida directa de calentamiento superficial por efecto invernadero. [7](https://science.nasa.gov/solar-system/temperatures-across-our-solar-system/); [8](https://science.nasa.gov/science-research/planetary-science/nasa-oxford-discover-warmer-uranus-than-once-thought/).

La temperatura efectiva representa la emisión planetaria total, no una lectura directa de la superficie. Las diferencias observadas reflejan la atmósfera y los límites del modelo de equilibrio uniforme. La serie entrega para Venus un albedo de 0,80; con ese dato se obtiene $T_e\approx220\ \mathrm K$. El capítulo teórico usa otro albedo de Venus y cita $244\ \mathrm K$, de modo que ese valor no es una comprobación directa de este cálculo. [1](<Serie_2.pdf>) (p. 1, tabla y perfil vertical); [2](<Cap2_Teoria_29_10_2024.pdf>) (pp. 6–8, tabla 2.2); [3](<Cap2_Slides_30_11_2025.pptx>) (diap. 10–12).

### 4. Luminosidad solar reducida

> [!quote] Enunciado 4
> Calcule a temperatura de emissão da Terra considerando que a luminosidade solar é inferior em 30% (de acordo com o que parece ter acontecido nas fases iniciais do sistema solar). Use o albedo e a distância Terra-Sol atuais nos seus cálculos.

#### Resolución

«Inferior en 30 %» significa que queda el 70 % del valor actual: $L'=0{,}70L_\odot$. Como $S\propto L$ a distancia fija, $S'=0{,}70S_0$. Con el albedo terrestre de la serie, $\alpha_p=0{,}30$, la temperatura escala como la cuarta raíz de la irradiancia:

$$
T'_e=T_e(0{,}70)^{1/4}
=255{,}44\ \mathrm K\,(0{,}70)^{1/4}
\approx233{,}64\ \mathrm K.
$$

La nueva temperatura efectiva es cerca de $21{,}79\ \mathrm K$ menor que la calculada con la luminosidad actual. La comprobación de escala es importante: una caída del 30 % en flujo no produce una caída del 30 % en temperatura, porque $T_e\propto S^{1/4}$. Este cálculo idealizado conserva fijos la distancia y el albedo. [1](<Serie_2.pdf>) (p. 2); [2](<Cap2_Teoria_29_10_2024.pdf>) (pp. 6–8).

### 5. Albedo de océano despejado

> [!quote] Enunciado 5
> Implicações de alterações relativamente pequenas. Calcular a temperatura de emissão da Terra, considerando que o albedo planetário é alterado para o das áreas oceânicas sem nuvens (cerca de 10%). Interprete os resultados tendo em conta as figuras de baixo. Use a distância Terra-Sol atuais nos seus cálculos.

#### Resolución

Tomamos la hipótesis del enunciado literalmente: el planeta completo pasa a tener $\alpha_p=0{,}10$, manteniendo la luminosidad y la distancia actuales. Entonces

$$
T_e=\left(\frac{(1-0{,}10)S_0}{4\sigma}\right)^{1/4}
=255{,}44\ \mathrm K\left(\frac{0{,}90}{0{,}70}\right)^{1/4}
\approx272{,}00\ \mathrm K.
$$

El resultado es unos $16{,}56\ \mathrm K$ mayor que el valor de referencia con albedo 0,30. El océano sin nubes de la imagen refleja menos radiación que el promedio del planeta supuesto en el modelo; al reducirse la reflexión, aumenta la energía absorbida. Las fotografías también muestran que la Tierra real combina océanos, continentes, nubes y noche. Por eso el cálculo no predice una nueva temperatura real: reemplaza toda esa distribución por un albedo uniforme del 10 %. [1](<Serie_2.pdf>) (p. 2, figuras «Terra vista da Lua» y «Terra fotografada do espaço»); [2](<Cap2_Teoria_29_10_2024.pdf>) (pp. 6–8).

### 6. Distancia Tierra–Sol reducida

> [!quote] Enunciado 6
> Implicações de alterações relativamente pequenas. Calcular as variações de constante solar e da temperatura de emissão em consequência de uma diminuição da distância Sol-Terra de 2%. Use o albedo e a distância Terra-Sol atuais nos seus cálculos.

#### Resolución

Una disminución del 2 % produce $d'=0{,}98d$. Por el inverso del cuadrado,

$$
\frac{S'}{S_0}=\left(\frac{d}{d'}\right)^2=\frac{1}{0{,}98^2}=1{,}04123.
$$

Usando $S_0=1379{,}34\ \mathrm{W\,m^{-2}}$ de los datos de la serie,

$$
S'=1436{,}22\ \mathrm{W\,m^{-2}},\qquad
\Delta S=+56{,}87\ \mathrm{W\,m^{-2}}\quad(+4{,}12\%).
$$

Con el albedo fijo, $T_e\propto S^{1/4}$:

$$
T'_e=T_e\left(\frac{S'}{S_0}\right)^{1/4}
=255{,}44\ \mathrm K\,(1{,}04123)^{1/4}
=258{,}03\ \mathrm K,
$$

por lo que $\Delta T_e\approx+2{,}59\ \mathrm K$. El aumento de temperatura es menor, en porcentaje, que el de irradiancia. Si se linealiza para cambios pequeños, $\Delta S/S\approx-2\Delta d/d$ y $\Delta T_e/T_e\approx\tfrac14\Delta S/S$; para el 2 % usamos arriba la relación exacta. [1](<Serie_2.pdf>) (p. 2); [2](<Cap2_Teoria_29_10_2024.pdf>) (pp. 5–8).

### 7. Una capa atmosférica opaca

> [!quote] Enunciado 7
> Defina um modelo do balanço radiativo com uma camada atmosférica com temperatura $T_a$ e uma superfície com temperatura $T_s$. Utilize um albedo planetário $\alpha_p$. Assuma que a superfície comporta-se como um corpo negro para a radiação terrestre, enquanto a atmosfera é transparente para a radiação solar, mas totalmente opaca para a radiação terrestre. Escreva as equações de balanço energético na superfície, na atmosfera e no topo da atmosfera.

#### Resolución

Sea $S_0$ la irradiancia solar perpendicular a los rayos, $\alpha_p$ el albedo planetario y

$$
F=\frac{(1-\alpha_p)S_0}{4}=\sigma T_e^4
$$

el flujo solar global medio absorbido. La superficie absorbe ese flujo y la emisión infrarroja descendente de la atmósfera, $\sigma T_a^4$; emite $\sigma T_s^4$. La capa opaca absorbe toda la emisión superficial y emite como cuerpo negro en ambas direcciones. El espacio recibe la emisión ascendente de la capa. Los tres balances por unidad de área son

$$
\begin{aligned}
\text{superficie:}&\quad F+\sigma T_a^4=\sigma T_s^4,\\
\text{atmósfera:}&\quad \sigma T_s^4=2\sigma T_a^4,\\
\text{TOA:}&\quad F=\sigma T_a^4.
\end{aligned}
$$

TOA significa techo de la atmósfera. Las ecuaciones son compatibles: de la tercera, $T_a=T_e$; de la segunda, $T_s=2^{1/4}T_e$. En la superficie, $F+F=2F$ confirma el balance. Son hipótesis de un modelo de una capa negra, no una descripción completa de la atmósfera real. [1](<Serie_2.pdf>) (p. 2); [2](<Cap2_Teoria_29_10_2024.pdf>) (pp. 14–15, fig. 2.10); [3](<Cap2_Slides_30_11_2025.pptx>) (diap. 31–34).

### 8. Dos capas atmosféricas opacas

> [!quote] Enunciado 8
> Considere o modelo de efeito de estufa de duas camadas no qual a atmosfera é representada por duas camadas perfeitamente absorventes, de temperaturas $T_A$ e $T_B$. Assuma que a superfície comporta-se como um corpo negro para a radiação terrestre, enquanto as várias camadas da atmosfera são transparentes para a radiação solar, mas totalmente opacas para a radiação terrestre. Determine estas temperaturas, bem como a temperatura de superfície $T_S$, em função da temperatura efetiva.

#### Resolución

Para fijar la notación, llamamos A a la capa superior y B a la inferior. Ambas son transparentes a la radiación solar, absorben todo el infrarrojo que reciben y emiten como cuerpos negros hacia arriba y hacia abajo. Sea $F=\sigma T_e^4$.

El balance en el techo de la atmósfera y el de la capa superior dan

$$
F=\sigma T_A^4,\qquad \sigma T_B^4=2\sigma T_A^4.
$$

La primera ecuación implica $T_A=T_e$. La capa B emite $2\sigma T_B^4$ en total y absorbe la emisión de la superficie más la emisión descendente de A:

$$
\sigma T_S^4+\sigma T_A^4=2\sigma T_B^4.
$$

Como $\sigma T_A^4=F$ y $\sigma T_B^4=2F$, resulta $\sigma T_S^4=3F$. Así,

$$
T_A=T_e,\qquad T_B=2^{1/4}T_e,\qquad T_S=3^{1/4}T_e.
$$

La superficie recibe $F$ de Sol y $2F$ de la capa inferior; emite $3F$. La secuencia $T_S>T_B>T_A=T_e$ verifica que las capas inferiores deben estar más calientes para que el mismo flujo $F$ escape al espacio. [1](<Serie_2.pdf>) (p. 2); [3](<Cap2_Slides_30_11_2025.pptx>) (diap. 35–36).

### 9. Una capa parcialmente absorbente

> [!quote] Enunciado 9
> Considere um modelo radiativo de uma camada atmosférica com temperatura $T_A$ e uma superfície com temperatura $T_S$. Assuma que a superfície comporta-se como um corpo negro para a radiação terrestre, enquanto a atmosfera é transparente para a radiação solar, mas tem absorvidade $a$ para a radiação terrestre.
>
> **a)** Escreva as equações de balanço energético na superfície, na atmosfera e no topo da atmosfera e obtenha as temperaturas de equilíbrio em função de $a$.
>
> **b)** Quanto muda a temperatura da superfície se $a$ aumentar de 0.8 para 0.9? Considere um albedo planetário de $\alpha_p=0.3$.

#### a) Balances y temperaturas

La atmósfera absorbe la fracción $a$ de la radiación superficial, y transmite $1-a$. El modelo docente supone emisividad atmosférica igual a absorptividad, también $a$, y emisión en las dos direcciones. Definimos $F=\sigma T_e^4$ como en el ejercicio 7. Los balances son

$$
\begin{aligned}
\text{superficie:}&\quad F+a\sigma T_A^4=\sigma T_S^4,\\
\text{atmósfera:}&\quad a\sigma T_S^4=2a\sigma T_A^4,\\
\text{TOA:}&\quad F=(1-a)\sigma T_S^4+a\sigma T_A^4.
\end{aligned}
$$

Para $a>0$, el balance atmosférico da $T_S^4=2T_A^4$. Al sustituirlo en el balance superficial,

$$
F=(2-a)\sigma T_A^4,
$$

y por tanto

$$
T_A=\left(\frac{1}{2-a}\right)^{1/4}T_e,
\qquad
T_S=\left(\frac{2}{2-a}\right)^{1/4}T_e.
$$

El balance TOA queda satisfecho por estas relaciones. Para $a=1$ se recupera la capa totalmente opaca: $T_S=2^{1/4}T_e$. En $a=0$, la superficie tiende a $T_e$, pero la ecuación atmosférica se reduce a $0=0$: una capa completamente transparente no tiene temperatura fijada radiativamente en este modelo. Las fórmulas para $T_A$ se aplican a $a>0$, no al caso exactamente transparente. [1](<Serie_2.pdf>) (pp. 2–3); [2](<Cap2_Teoria_29_10_2024.pdf>) (pp. 15–17); [3](<Cap2_Slides_30_11_2025.pptx>) (diap. 37–39).

#### b) Cambio al pasar de $a=0{,}8$ a $a=0{,}9$

Con los datos de la serie, $S_0=1379{,}34\ \mathrm{W\,m^{-2}}$, $\alpha_p=0{,}3$ y $\sigma=5{,}67\times10^{-8}\ \mathrm{W\,m^{-2}\,K^{-4}}$:

$$
T_e=\left(\frac{0{,}7S_0}{4\sigma}\right)^{1/4}=255{,}44\ \mathrm K.
$$

Entonces

$$
T_S(0{,}8)=\left(\frac{2}{1{,}2}\right)^{1/4}T_e=290{,}23\ \mathrm K,
$$

$$
T_S(0{,}9)=\left(\frac{2}{1{,}1}\right)^{1/4}T_e=296{,}61\ \mathrm K,
$$

$$
\Delta T_S=T_S(0{,}9)-T_S(0{,}8)=+6{,}38\ \mathrm K.
$$

El signo positivo indica calentamiento en este equilibrio idealizado: una capa más absorbente devuelve más infrarrojo a la superficie, que necesita alcanzar una temperatura mayor para mantener el flujo saliente. Las diapositivas redondean a 290 K y 296 K; la diferencia precisa con las constantes y el valor de $S_0$ de esta serie es $6{,}38$ K. [1](<Serie_2.pdf>) (p. 3); [3](<Cap2_Slides_30_11_2025.pptx>) (diap. 38–39).

### 10. Gases de efecto invernadero antropogénicos

> [!quote] Enunciado 10
> O que entende por gases de efeito de estufa antropogénicos? Identifique os mais importantes e o seu efeito no balanço radiativo da Terra.

#### Resolución

Un gas de efecto invernadero absorbe radiación infrarroja en bandas determinadas y puede emitirla según su estado térmico. Es **antropogénico** cuando las actividades humanas emiten el gas o alteran su concentración atmosférica. Entre los más importantes que destaca el capítulo están el dióxido de carbono procedente de la combustión y los cambios de uso del suelo, el metano asociado a extracción de combustibles y agricultura, el óxido nitroso relacionado con suelos y fertilizantes, y los clorofluorocarbonos usados industrialmente. El ozono también absorbe infrarrojo, aunque su concentración y efectos dependen de dónde se forme. El vapor de agua es el principal gas de efecto invernadero natural en abundancia, pero en el marco explicado actúa sobre todo como realimentación rápida al calentamiento. [2](<Cap2_Teoria_29_10_2024.pdf>) (pp. 10–13); [3](<Cap2_Slides_30_11_2025.pptx>) (diap. 18–29).

Al absorber parte de la radiación infrarroja emitida por la superficie, la atmósfera modifica la altura y temperatura desde las que la energía escapa al espacio. Parte de la radiación absorbida se reemite hacia arriba y parte hacia abajo. Si aumenta el forzamiento de onda larga, inicialmente sale menos energía de la que entra; el sistema se calienta hasta acercarse a un nuevo balance. El proceso aumenta la temperatura superficial respecto de la temperatura efectiva, aunque la magnitud real depende de bandas espectrales, nubes, convección y otros procesos. [2](<Cap2_Teoria_29_10_2024.pdf>) (pp. 8–15); [3](<Cap2_Slides_30_11_2025.pptx>) (diap. 27–39).

Las concentraciones y forzamientos numéricos del PDF corresponden a estimaciones históricas, algunas de antes de 2014; no se presentan aquí como actuales. La distinción relevante para resolver el enunciado es que las emisiones humanas modifican la opacidad infrarroja y, con ella, el balance de energía terrestre. NASA describe este intercambio entre radiación superficial y atmosférica dentro del presupuesto energético terrestre. [5](https://science.nasa.gov/earth/earth-observatory/climate-and-earths-energy-budget/).

### 11. Nitrógeno y oxígeno como gases mayoritarios

> [!quote] Enunciado 11
> Porque é que os principais constituintes da atmosfera ($N_2$, $O_2$) não são gases relevantes para o “efeito de estufa”?

#### Resolución

Las moléculas $\mathrm{N_2}$ y $\mathrm{O_2}$ están formadas por dos átomos iguales. Sus vibraciones no producen un cambio de momento dipolar eléctrico, necesario para acoplarse eficazmente con la radiación infrarroja en las bandas térmicas terrestres. Por eso estos gases, pese a ser los constituyentes más abundantes del aire seco, absorben muy poco infrarrojo en comparación con moléculas como $\mathrm{CO_2}$, $\mathrm{H_2O}$ o $\mathrm{CH_4}$, cuyos modos vibracionales sí interactúan con esa radiación. La abundancia por sí sola no determina la importancia de un gas para el efecto invernadero. [2](<Cap2_Teoria_29_10_2024.pdf>) (pp. 2–3, 12–13); [3](<Cap2_Slides_30_11_2025.pptx>) (diap. 27–29).

### 12. Dispersión de Rayleigh y cielo azul

> [!quote] Enunciado 12
> Indique de forma sumária o mecanismo de difusão de Rayleigh e justifique a partir dele o motivo pelo qual vemos o céu azulado.

#### Resolución

La dispersión de Rayleigh ocurre cuando las partículas dispersoras son mucho menores que la longitud de onda: $r\ll\lambda$. El campo electromagnético induce oscilaciones en la carga de las moléculas y estas reemiten radiación en distintas direcciones. En este régimen, la intensidad dispersada varía aproximadamente como

$$
I_{\mathrm{dispersada}}\propto\lambda^{-4}.
$$

La luz azul de $490\ \mathrm{nm}$ se dispersa más que la roja de $700\ \mathrm{nm}$. Con la dependencia indicada,

$$
\frac{I_{490}}{I_{700}}\approx\left(\frac{700}{490}\right)^4\approx4{,}16.
$$

Por eso, al mirar en direcciones alejadas del disco solar, llega luz azul dispersada por la atmósfera desde muchas direcciones. Cerca del Sol predomina la luz directa, empobrecida relativamente en longitudes de onda cortas, y el cielo puede verse rojizo. El boletín y las diapositivas citan un factor 9,4 para 490 y 700 nm; no se obtiene de $\lambda^{-4}$ con esas longitudes de onda, por lo que se señala como errata numérica del material. También debe distinguirse la **dispersión de Rayleigh** de la **ley de Rayleigh–Jeans**, que se refiere a una aproximación clásica del espectro de cuerpo negro. La exposición de la dispersión por electrones ligados y partículas pequeñas de UT Austin confirma la dependencia con la longitud de onda. [1](<Serie_2.pdf>) (p. 3); [2](<Cap2_Teoria_29_10_2024.pdf>) (pp. 19–20); [3](<Cap2_Slides_30_11_2025.pptx>) (diap. 49–57); [6](https://farside.ph.utexas.edu/teaching/jk1/lectures/node108.html).

### 13. Aerosoles y balance radiativo

> [!quote] Enunciado 13
> Um dos processos importantes que tem lugar na camada limite atmosférica é o transporte, de partículas originárias dos processos de superfície ou originada nos processos químicos internos à atmosfera, e denominados coletivamente por aerossóis. (a) Esclareça o papel destas partículas no equilíbrio radiativo; (b) Descreva as principais categorias de aerossóis e a sua importância relativa; (c) Diga o que entende por tempo de residência de um aerossol.

#### a) Papel radiativo

Los aerosoles dispersan radiación solar; algunas partículas también la absorben. La dispersión hacia el espacio reduce la energía solar absorbida por el sistema y suele favorecer un efecto de enfriamiento. El signo y la magnitud de la absorción dependen de la composición, el tamaño, la altura y la superficie inferior. De forma indirecta, los aerosoles pueden actuar como núcleos de condensación: modificar el número y tamaño de gotas cambia las propiedades ópticas de las nubes y su reflexión de onda corta. El efecto neto no es idéntico para todas las partículas. [2](<Cap2_Teoria_29_10_2024.pdf>) (pp. 18–20); [3](<Cap2_Slides_30_11_2025.pptx>) (diap. 49–59).

#### b) Categorías y abundancia relativa

Hay dos distinciones complementarias. Por formación, un aerosol es **primario** si entra directamente al aire como partícula —por ejemplo, polvo, sal marina o humo— y **secundario** si se forma en la atmósfera a partir de gases por nucleación y crecimiento. Por aspecto y tamaño, el material docente distingue:

| Categoría del material | Fase y tamaño aproximado | Ejemplos |
|---|---|---|
| Emisiones y humos | Partículas sólidas finas, desde 1 nm ($0{,}001\ \mu\mathrm m$) hasta menos de unos 10 $\mu\mathrm m$ en los ejemplos | Combustión incompleta de carbón, petróleo o gas |
| Polvo | Partículas sólidas, aproximadamente 1–100 $\mu\mathrm m$ | Suelo, arena, carbón, cemento y polen |
| Névoas o nieblas | Gotas líquidas menores de 10 $\mu\mathrm m$ | Gotas de agua suspendidas |
| Sprays | Gotas líquidas mayores de 10 $\mu\mathrm m$ | Salpicadura marina o producción humana |

El PDF estima que alrededor de tres cuartas partes de las emisiones de aerosoles serían naturales y una cuarta parte humanas. Es una proporción histórica y aproximada, dependiente del tamaño de partícula considerado y del inventario. La abundancia de una fuente no fija por sí sola su efecto climático: también importan composición, duración, altura e interacción con las nubes. [2](<Cap2_Teoria_29_10_2024.pdf>) (pp. 17–18, tabla 2.3); [3](<Cap2_Slides_30_11_2025.pptx>) (diap. 40–47).

#### c) Tiempo de residencia

El **tiempo de residencia** es el tiempo característico que las partículas permanecen en la atmósfera entre su entrada y su eliminación. El material docente da como orden típico desde unos días hasta una semana. Durante ese lapso pueden coagularse, condensar material, evaporarse o reaccionar dentro de nubes; salen del aire mediante deposición seca, como sedimentación y difusión, o deposición húmeda con la precipitación. Un tiempo corto suele concentrar sus efectos cerca de las fuentes, aunque algunas partículas pueden transportarse a distancia antes de depositarse. [2](<Cap2_Teoria_29_10_2024.pdf>) (p. 18); [3](<Cap2_Slides_30_11_2025.pptx>) (diap. 48).

### 14. Parámetro de tamaño para partículas en el visible

> [!quote] Enunciado 14
> Considere os diâmetros médios típicos das seguintes partículas atmosféricas: moléculas de ar, $10^{-10}$–$10^{-11}\ \mathrm m$; núcleos de condensação (por exemplo, fumos), $10^{-7}$–$10^{-8}\ \mathrm m$; poeiras, $10^{-7}\ \mathrm m$; gotículas das nuvens, $10^{-5}\ \mathrm m$; gotas de precipitação, $10^{-3}\ \mathrm m$; gotas de aguaceiros e granizo, $10^{-3}$–$10^{-1}\ \mathrm m$. Para cada caso determine o valor do parâmetro $\alpha$ para a radiação na banda do visível e identifique o processo dominante de interação com a radiação.

#### Resolución

El parámetro de tamaño compara una longitud característica de la partícula con la longitud de onda. En la nota teórica y las diapositivas se denota $x=2\pi r/\lambda$. Como el enunciado da el diámetro $D=2r$, su parámetro es

$$
\alpha_{\mathrm{size}}\equiv x=\frac{\pi D}{\lambda}.
$$

Esta $\alpha_{\mathrm{size}}$ es adimensional y **no es** el albedo planetario $\alpha_p$. Para obtener valores comparables usamos una longitud de onda representativa de la luz visible, $\lambda=0{,}55\ \mu\mathrm m=5{,}5\times10^{-7}\ \mathrm m$. Los límites orientativos son $\alpha_{\mathrm{size}}\ll1$ para Rayleigh, del orden de uno para Mie y mucho mayor que uno para el régimen geométrico.

```anki
deck: Física::Terra, Ambiente e Clima::Balance radiativo
tags:
  - fisica
  - clima
  - radiacion
---
> [!note] Pregunta
> ¿Qué diferencia hay entre $\alpha_p$ y $\alpha_{\mathrm{size}}$ en el ejercicio de aerosoles?
===
> [!important] Respuesta
> $\alpha_p$ es el albedo planetario: la fracción de radiación solar reflejada por el planeta. $\alpha_{\mathrm{size}}=\pi D/\lambda$ es un parámetro adimensional que compara el tamaño de una partícula con la longitud de onda y orienta el régimen de interacción con la luz.
```

| Partícula | Diámetro $D$ (m) | $\alpha_{\mathrm{size}}=\pi D/\lambda$ | Régimen e interacción dominante |
|---|---:|---:|---|
| Moléculas del aire | $10^{-11}$–$10^{-10}$ | $5{,}7\times10^{-5}$–$5{,}7\times10^{-4}$ | Rayleigh: dispersión molecular, muy selectiva con la longitud de onda |
| Núcleos de condensación / humos | $10^{-8}$–$10^{-7}$ | 0,057–0,57 | De Rayleigh hacia la transición a Mie; el extremo grande ya no es claramente $\ll1$ |
| Polvo | $10^{-7}$ | 0,57 | Transición Rayleigh–Mie; dispersión selectiva que empieza a perder la aproximación de partícula muy pequeña |
| Gotas de nube | $10^{-5}$ | 57 | Régimen geométrico como aproximación; dispersión y refracción por gotas grandes frente a la onda |
| Gotas de precipitación | $10^{-3}$ | $5{,}7\times10^3$ | Régimen geométrico |
| Gotas de aguacero y granizo | $10^{-3}$–$10^{-1}$ | $5{,}7\times10^3$–$5{,}7\times10^5$ | Régimen geométrico |

Los valores dependen de la longitud de onda exacta dentro del visible, que abarca aproximadamente 0,4–0,7 $\mu\mathrm m$. La elección de 0,55 $\mu\mathrm m$ permite una comparación común. No altera la clasificación de moléculas ni de gotas grandes, pero los humos y el polvo quedan cerca de la transición entre Rayleigh y Mie. Para partículas de esos tamaños, es más prudente indicar un régimen transicional que asignar una frontera exacta. En la descripción de Mie y la óptica geométrica se usan radios comparados con $\lambda$; aquí el factor $\pi$ ya convierte correctamente el diámetro a la forma $2\pi r$. [1](<Serie_2.pdf>) (p. 3, tabla); [2](<Cap2_Teoria_29_10_2024.pdf>) (pp. 19–20); [3](<Cap2_Slides_30_11_2025.pptx>) (diap. 49–57).

## 📚 Fuentes

### Material base

- [1. Ricardo Machado Trigo — *Terra, Ambiente e Clima*, Série Nº 2](<Serie_2.pdf>) (pp. 1–3). Enunciados y datos de los catorce ejercicios. El documento no incluye soluciones.
- [2. Ricardo Machado Trigo — *Terra, Ambiente e Clima*, capítulo 2, «Balanço Radiativo»](<Cap2_Teoria_29_10_2024.pdf>) (21 pp.). Relaciones físicas, constantes solares y planetarias, efecto invernadero, modelos de capas y aerosoles.
- [3. Ricardo Machado Trigo — *Terra, Ambiente e Clima*, diapositivas del capítulo 2, curso 2025/26](<Cap2_Slides_30_11_2025.pptx>) (59 diap.). Ejemplos de modelos de una, dos y opacidad parcial; aerosol, dispersión y presupuestos radiativos.

### Fuentes externas de contraste

- [4. OpenStax, *University Physics*, vol. 3, §6.1 — Blackbody Radiation](https://openstax.org/books/university-physics-volume-3/pages/6-1-blackbody-radiation). Emisión de cuerpo negro, leyes de Stefan–Boltzmann y Wien, y distinción entre dispersión de Rayleigh y ley de Rayleigh–Jeans.
- [5. NASA Science — Climate and Earth’s Energy Budget](https://science.nasa.gov/earth/earth-observatory/climate-and-earths-energy-budget/). Balance radiativo planetario e intercambio de energía entre superficie y atmósfera.
- [6. University of Texas at Austin — Rayleigh Scattering](https://farside.ph.utexas.edu/teaching/jk1/lectures/node108.html). Mecanismo de dispersión por partículas pequeñas.
- [7. NASA Science — Temperatures Across Our Solar System](https://science.nasa.gov/solar-system/temperatures-across-our-solar-system/). Aclara que los gigantes gaseosos no poseen una superficie sólida y que sus temperaturas se citan para un nivel atmosférico definido por presión.
- [8. NASA Science — NASA, Oxford Discover Warmer Uranus Than Once Thought](https://science.nasa.gov/science-research/planetary-science/nasa-oxford-discover-warmer-uranus-than-once-thought/). Explica que Júpiter, Saturno y Neptuno emiten más energía de la que reciben del Sol, debido a su calor interno.

### Trazabilidad de los cálculos

Las irradiancias y temperaturas de los ejercicios 1–6 se recalcularon con las constantes impresas en la serie: $L_\odot=3{,}9\times10^{26}\ \mathrm W$, $1\ \mathrm{AU}=1{,}50\times10^{11}\ \mathrm m$ y $\sigma=5{,}67\times10^{-8}\ \mathrm{W\,m^{-2}\,K^{-4}}$. Los ejercicios 7–9 usan las hipótesis explícitas de la serie y se cotejan con los diagramas y casos numéricos de las diapositivas. Los ejercicios 10–14 siguen el contenido conceptual del capítulo y del material de clase. Ninguna resolución se atribuye al profesor como solucionario oficial.

## 🧑‍🏫 Prompt para tutor conversacional

Actúa como tutor universitario introductorio de *Terra, Ambiente e Clima*. Trabaja un ejercicio cada vez y espera la respuesta del estudiante. Pide primero identificar datos, incógnitas, unidades e hipótesis; luego solicita el balance o relación física antes de introducir números. Comprueba en particular el factor geométrico $1/4$, la dependencia $S\propto d^{-2}$, la cuarta raíz en las temperaturas, la diferencia entre temperatura efectiva y superficial, los balances TOA/superficie de las capas y la distinción entre $\alpha_p$ y $\alpha_{\mathrm{size}}$. Si aparece un error, ofrece una pista sobre dimensiones, signo o caso límite antes de mostrar el paso completo. Cierra con la interpretación física y el alcance del modelo.
