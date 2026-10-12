# Explotación de poblaciones

> + **_Tipo de material_**: <span style="display: inline-block; font-size: 12px; color: white; background-color: #029BF9; border-radius: 5px; padding: 5px; font-weight: bold;"> Teoría</span> <span style="display: inline-block; font-size: 12px; color: white; background-color: #E68532; border-radius: 5px; padding: 5px; font-weight: bold;"> Aplicación</span>
> + **_Versión_**: 2026-2027
> + **_Asignatura (grado)_**: Ecología (CCAA)
> + **_Autor_**: Curro Bonet-García (fjbonet@uco.es)
> + **Duración**: Aproximadamente 2 sesiones de 1 hora.



![portada](https://raw.githubusercontent.com/aprendiendo-cosas/Te_poblaciones_explotacion_ecologia_ccaa/2026_2027/imagenes/portada.jpg)

[TOC]





## 1. Objetivos 

En esta guía se describen dos sesiones de una hora cada una. Tiene los siguientes objetivos. 

+ Aprendizaje de los conceptos básicos que, procedentes de la ecología de poblaciones, rigen las técnicas de extracción de biomasa de poblaciones en la naturaleza. 
+ Comprender una aplicación práctica de la idea de reclutamiento procedente de la dinámica de poblaciones.
+ Cuestionar la simplicidad de las técnicas de manejo analizadas: constatar la necesidad de utilizar conceptos más elaborados (manejo de ecosistemas en lugar que de especies).

Este acto docente consta de dos sesiones diferentes que se describen a continuación: "Conceptos generales sobre explotación de poblaciones" y "Aplicaciones de la explotación de poblaciones".

El tema de la explotación de poblaciones es muy importante en ecología y quizás más para los estudiantes de ciencias ambientales. Los fundamentos teóricos que describimos en esta sesión son necesarios para entender el nacimiento de técnicas tan importantes como la selvicultura, la gestión cinegética o la gestión de recursos piscícolas. 



## 2. Pregunta inicial

Los contenidos descritos a continuación se inician con una pregunta "[bisagra](https://investigaciondocente.com/2019/08/10/rtcomo-podemos-monitorizar-el-pensamiento-de-nuestros-estudiantes/)" propuesta en la sesión anterior (en la que estudiamos la competencia intraespecífica). A continuación se vuelve a mostrar dicha pregunta:

![grafica_logistica](https://raw.githubusercontent.com/aprendiendo-cosas/Te_poblaciones_explotacion_ecologia_ccaa/2025_2026/imagenes/Logisticpopulationgrowth2.jpg)


*Fuente: Wikimedia*

>Observa  con detenimiento la siguiente gráfica. Muestra cómo cambia a lo largo del tiempo el tamaño de una población en la que hay competencia intraespecífica. Imagina que se trata de la curva de crecimiento teórico de, por ejemplo, una población de truchas en una piscifactoría o una población de conejos en un coto de caza. Es decir, hablamos de una población de la que nosotros podemos extraer invididuos. Si sabemos que los individuos de la especie estudiada compiten y que el crecimiento poblacional se frena al acercarse a la capacidad de carga, ¿cómo podemos aprovechar ese conocimiento para explotar la población de forma sostenible?. O dicho de otra forma, ¿en qué momento del proceso de crecimiento de la población podemos maximizar la extracción de individuos sin afectar a la sostenibilidad de la población?



La gestión de recursos biológicos renovables (como la explotación forestal, cinegética o pesquera) descansa sobre una disyuntiva operativa fundamental: **cómo maximizar la extracción continuada de biomasa sin comprometer la persistencia y viabilidad demográfica de la población explotada**. Ambos objetivos presentan una tensión inherente:

- Una extracción nula preserva de forma estricta la población, pero anula el rendimiento socioeconómico.
- Una extracción que intente capturar la totalidad de la biomasa disponible conduce de manera directa al colapso poblacional.

Para resolver formalmente este compromiso (*trade-off*), es imprescindible analizar la dinámica poblacional subyacente y, en particular, los mecanismos de regulación dependientes de la densidad derivados de la competencia intraespecífica.



## 3. Primeras respuestas a la pregunta

El dilema inicial surge al decidir en qué fase del crecimiento poblacional conviene intervenir para conseguir los dos objetivos planteados:



### 3.1 Extracción en fases iniciales ($N < K/2$)

Cuando la población se encuentra en densidades bajas respecto a la capacidad de carga: 

- La estructura demográfica se compone predominantemente de cohortes juveniles que aún no han alcanzado su madurez sexual ni han contribuido plenamente a la reproducción. 
- Extraer biomasa en este tramo sustrae capacidad reproductiva antes de que opere la autorregulación por competencia intraespecífica. Como consecuencia, la tasa de recuperación poblacional se aplana notablemente, dilatando el tiempo necesario para reponer el número de individuos inicial. 

### 3.2 Extracción en fases maduras ($N > K/2$)

En densidades intermedias-altas: 

- La población cuenta con abundancia de individuos adultos sometidos a una intensa competencia intraespecífica. 
- Al extraer individuos en este sector, se alivia deliberadamente la presión competitiva. Al suprimirse temporalmente ese freno, la tasa neta de crecimiento de los individuos remanentes se incrementa, acelerando la recuperación de la biomasa hacia el equilibrio. 

Existen dos estrategias básicas para articular la explotación:

1. **Regulación por esfuerzo fijo** (mantenimiento constante de los medios de captura, permitiendo que la cosecha varíe en función de la abundancia).
2. **Regulación por cuota fija** (establecimiento de una extracción cuantitativa constante de biomasa por unidad de tiempo: $H = \text{constante}$).



## 4. Modelización de la explotación bajo Cuota Fija ($H$)

Bajo el régimen de cuota fija, la ecuación diferencial de la población pasa a ser:

$$\frac{dN}{dt} = r \cdot N \left( \frac{K - N}{K} \right) - H$$

Gráficamente, la cuota $H$ se proyecta como una recta horizontal sobre la curva de reclutamiento:

![cuota_fija](https://raw.githubusercontent.com/aprendiendo-cosas/Te_poblaciones_explotacion_ecologia_ccaa/refs/heads/main/imagenes/cuota_fija.png)



### 4.1 Tipología de equilibrios bajo cuota fija:

1. **Cuota excesiva ($H_0 > H_{\text{máx}}$)**:

   La tasa de extracción supera en todo momento la capacidad máxima intrínseca de renovación de la población. Dado que $\frac{dN}{dt} < 0$ para cualquier densidad, la extinción es el resultado determinista inevitable.

2. **Cuota subcrítica ($H_1 < H_{\text{máx}}$)**:

   La recta de cosecha interseca la curva de reclutamiento en dos puntos de equilibrio donde $\frac{dN}{dt} = 0$:

   - **Punto A ($N_A < K/2$, equilibrio inestable)**: Si la población experimenta una perturbación negativa o una sobreextracción puntual que sitúe a $N$ por debajo de $N_A$, la tasa de extracción superará al reclutamiento ($H > dN/dt$), conduciendo a la población a una espiral de declive irreversible hacia la extinción.
   - **Punto B ($N_B > K/2$, equilibrio dinámicamente estable)**: Si la biomasa disminuye ligeramente, la población entra en una zona donde el reclutamiento supera la cuota extraída ($dN/dt > H$), lo que permite su recuperación espontánea hacia $N_B$. Asimismo, este punto opera retirando individuos en un entorno donde se relaja la competencia intraespecífica, asegurando la sostenibilidad a largo plazo.

3. **Cuota tangencial o Máximo Rendimiento Sostenible ($H_2 = H_{\text{MSY}}$)**:

   La extracción coincide con la cima parabólica del reclutamiento ($N = K/2$). En términos teóricos, maximiza el rendimiento económico sostenido. No obstante, **constituye un equilibrio frágil y metaestable**: cualquier fluctuación ambiental adversa desplaza el sistema hacia la izquierda del punto crítico, situándolo en la zona de extinción estocástica sin capacidad intrínseca de retorno.

### 4.2 Limitaciones de la cuota fija
El modelo clásico de extracción mediante cuota fija ($H = \text{constante}$) presenta serias restricciones operativas y biológicas al fundamentarse en supuestos deterministas difícilmente verificables en la naturaleza. Entre sus principales debilidades destacan:

1. La asunción de homogeneidad intraespecífica (ignora variaciones ontogénicas, estructura de edades y clases de tamaño).
2. La consideración de una capacidad de carga estática ($K = \text{constante}$), cuando empíricamente fluctúa de forma estacional e interanual en respuesta a forzamientos ambientales.
3. La dificultad inherente a censar con precisión el tamaño poblacional ($N$) y estimar la curva real de reclutamiento.

### 4.3 Discusión de dudas  planteadas por el alumnado

#### 4.3.1 Duda 1: ¿Por qué no dejar crecer la población hasta la saturación ($K$) y luego extraer de golpe la mitad (K/2)?

*Análisis demográfico y de gestión:*

Aunque intuitiva, esta alternativa presenta severos inconvenientes:  

- **Coste de oportunidad temporal**: Obliga a periodos de espera improductivos prolongados mientras la biomasa se aproxima asintóticamente a $K$, durante los cuales el rendimiento neto es nulo.   
- **Inestabilidad por desfases temporales (oscilaciones)**: En poblaciones naturales (especialmente aquellas con retrasos temporales intrínsecos o estrategias de la $r$), el acercamiento a $K$ suele generar oscilaciones amortiguadas o ciclos límite. El gestor no puede determinar con certeza si la población se encuentra en la fase de cresta o en la de declive post-saturación.   
- **Riesgos sanitarios dependientes de la densidad**: En condiciones de confinamiento o máxima densidad poblacional, proliferan patógenos, estrés metabólico y competencia interferente severa, incrementando la vulnerabilidad del stock.   


#### 4.3.2 Duda 2: Interacción entre cuotas fijas, periodos de veda y fenología

*Planteamiento:*
Si se establecen vedas temporales que respeten la época de reproducción, ¿garantiza esto la sostenibilidad de una cuota fija con independencia del tamaño del stock? 

*Análisis demográfico:*
Es crítico distinguir entre dos dimensiones biológicas independientes: 

1. **La fenología reproductiva**: Determina *cuándo* tiene lugar el proceso biológico de reproducción dentro del ciclo estacional. La instauración de vedas y la selectividad de artes (mallas de red de luz adecuada) aseguran que los individuos juveniles alcancen la madurez y que los adultos puedan realizar las puestas o partos. 

2. **El balance numérico del stock**: Determina *cuántos* individuos pueden retirarse de forma sostenible una vez concluido el periodo reproductor. 

   Aunque una veda proteja con éxito la fase de reproducción, si el tamaño poblacional global se encuentra en el dominio de inestabilidad ($N < K/2$), la extracción de una cuota fija que exceda la tasa de adición neta del año provocará el colapso demográfico. La protección temporal es una condición necesaria pero no suficiente si el volumen absoluto extraído desborda el reclutamiento neto. 

#### 4.3.3. Duda 3: La incertidumbre empírica sobre $K$ y el forzamiento ambiental

En sistemas abiertos (como las pesquerías de peces pelágicos en mar abierto): 

- Es inviable censar la totalidad de individuos o determinar con precisión matemática la capacidad de carga K y su punto medio $K/2$. 
- Factores oceanográficos y meteorológicos de gran escala (como los episodios de El Niño-Oscilación del Sur) reconfiguran drásticamente los parámetros de productividad primaria, provocando que $K$ oscile de un año a otro. 
- Los gestores se ven forzados a deducir el estado de la población de manera indirecta a partir del rendimiento por unidad de esfuerzo  o desembarcos comerciales. Por tanto, operar bajo una cuota rígida en las proximidades del Máximo Rendimiento Sostenible (K/2) resulta temerario; la prudencia biológica aconseja fijar cuotas conservadoras situadas claramente en la rama derecha y estable de la curva ($N > K/2$). 



## 5. Modelización de la explotación bajo Esfuerzo fijo ($E$)

Como alternativa más robusta frente al riesgo de colapso demográfico, se formalizó el modelo de **esfuerzo fijo** ($E = \text{constante}$). En lugar de predeterminar un volumen rígido de biomasa a retirar en cada ciclo, se limita la intensidad o los medios de captura aplicados (por ejemplo, número de embarcaciones operativas, artes de pesca desplegadas o tiempo de faena).

### 5.1. Formalización matemática y comportamiento gráfico del modelo

Bajo el régimen de esfuerzo constante, la cosecha instantánea ($H$) no es un valor fijo, sino una función dependiente de la densidad del stock disponible:

$$H(N) = q \cdot E \cdot N$$

donde:

- *E* representa el esfuerzo de extracción.
- *q* simboliza el coeficiente de capturabilidad (fracción de la población capturada por unidad de esfuerzo aplicada). 
- *N* representa el tamaño o biomasa de la población.



En el plano donde se confronta el reclutamiento neto frente al tamaño poblacional, la función de cosecha bajo esfuerzo fijo deja de ser una recta horizontal y pasa a ser una **recta con pendiente positiva**  que nace en el origen de coordenadas:



```
Reclutamiento / Cosecha
      ^
      |      / E_0 (Esfuerzo excesivo: pendiente muy elevada)
      |     /      .---.
      |    /      /     \   / E_MSY (Esfuerzo óptimo tangencial en K/2)
      |   /      /       \ /
      |  /      /   *     *
      | /      /   /|\   /|\
      |/      *---/-|- -/-|-\------ E_bajo (Esfuerzo moderado: pendiente suave)
      +------(---/--+--/--+--)--------> N (Tamaño poblacional)
     0       A     K/2    B  K

```

A diferencia de la cuota fija —donde a densidades bajas el esfuerzo humano debe dispararse exponencialmente para alcanzar el objetivo fijado—, en el modelo de esfuerzo constante la biomasa capturada desciende de forma natural y proporcional si la abundancia poblacional decae (es decir, a menor densidad, menor captura efectiva).



### 5.2. Análisis de estabilidad y regímenes de esfuerzo

La interacción entre la curva parabólica de reclutamiento y la recta de esfuerzo delimita tres escenarios:

1. **Esfuerzo excesivo ($E_0$)**:
   La pendiente de la función de captura es superior a la tangente de la curva de reclutamiento en el origen. En este caso, la tasa de extracción supera la renovación intrínseca en cualquier nivel de densidad ($H(N) > \frac{dN}{dt}$), provocando de manera determinista la extinción del recurso.


2. **Esfuerzo subcrítico o moderado ($E_{\text{bajo}}$)**:
   La recta interseca la curva de reclutamiento en dos puntos: el origen $(0,0)$ y un punto de equilibrio $B$ situado en la rama derecha:
   
   * **Mecanismo autorregulador**: Si una perturbación ambiental reduce temporalmente la biomasa *N* por debajo de *N_B*, el reclutamiento supera de inmediato a la tasa de captura, impulsando a la población a retornar de forma espontánea al equilibrio *B*.
   
   * **Alivio de la competencia intraespecífica**: Al operar a densidades relativamente altas, la retirada de biomasa relaja la densodependencia negativa (reduce el freno competitivo), lo que incrementa la tasa neta de renovación de los individuos remanentes.


3. **Esfuerzo óptimo de Rendimiento Máximo Sostenible ($E_{\text{MSY}}$)**:
   La pendiente de la recta se ajusta para intersecionar la curva exactamente en su cúspide ($N = K/2$). Aunque maximiza el rendimiento biológico medio, presenta vulnerabilidad ante perturbaciones estocásticas que depriman la capacidad de renovación del sistema.



## 6 Estudio de caso: La pesquería de la anchoveta peruana (*Engraulis ringens*)

Para examinar las divergencias entre los modelos teóricos uniespecíficos y la gestión ecosistémica en el mundo real, se analizó la pesquería pelágica de la anchoveta peruana en el ecosistema de la Corriente de Humboldt.

### 6.1. Fundamento oceanográfico: Afloramiento costero (*upwelling*)

La elevada productividad biológica de la costa occidental sudamericana responde al régimen de surgencia costera forzado por los vientos alisios y la fuerza de Coriolis.

Este fenómeno arrastra aguas profundas ricas en nutrientes hacia la zona fótica superficial, estimulando explosiones de fitoplancton que sustentan redes tróficas cortas y de alta eficiencia con densas concentraciones de *Engraulis ringens*. Históricamente, esta especie ha representado cerca del 10% de las capturas marinas globales (entre 3 y 12 millones de toneladas métricas anuales).

### 6.2. El Niño (ENSO) y el colapso demográfico

La dinámica de la pesquería ha estado marcada por perturbaciones cíclicas de macroescala:

A continuación se presenta la reescritura del fragmento en un registro científico riguroso, depurando las digresiones orales e incorporando la terminología precisa de la dinámica de poblaciones y la oceanografía pesquera:



### 6.3 Dinámica histórica y colapso de la pesquería de anchoveta peruana (*Engraulis ringens*)

A principios de la década de 1970, la pesquería de anchoveta peruana (*Engraulis ringens*) experimentó un severo colapso demográfico provocado por la interacción sinérgica entre una sobreexplotación continuada del *stock* y el impacto anómalo del evento oceanográfico El Niño (ENSO) de 1972-1973. Durante este periodo, la comprensión científica y la capacidad de predicción del fenómeno ENSO eran aún incipientes, lo que retrasó la adopción de medidas de gestión proactivas. La falta de adaptación inmediata del esfuerzo pesquero y la implementación tardía de restricciones normativas resultaron insuficientes para mitigar el agotamiento biológico, consolidando la entrada del caladero en una fase de colapso demográfico e industrial.

La recurrencia de un episodio extraordinario de El Niño en 1982-1983 condujo a una virtual paralización de los desembarques comerciales. Este registro cercano a cero en las capturas no constituyó una extinción biológica de la especie, sino un colapso del rendimiento por unidad de esfuerzo (CPUE) asociado a la dispersión extrema de la biomasa remanente, a fallos críticos en el reclutamiento y a la inviabilidad económica de la detección y extracción en un hábitat oceánico de gran escala.

En respuesta a esta crisis sucesiva, las autoridades peruanas y organismos multilaterales establecieron a mediados de los años ochenta moratorias biológicas, vedas reproductivas y límites al esfuerzo pesquero, lo que permitió un proceso paulatino de recuperación del *stock*. A pesar de una nueva perturbación climática de gran magnitud a finales de los noventa (El Niño 1997-1998), la pesquería transitó hacia un marco de ordenación adaptativo fundamentado en el control del esfuerzo y el establecimiento de cuotas globales móviles. Si bien en el plano teórico este régimen aproxima la explotación a criterios de sostenibilidad, en la práctica el estado del recurso se mantiene sujeto a una elevada incertidumbre debido a la interacción de variables macroclimáticas no estacionarias, cambios de régimen decenales y presiones económicas globales difícilmente parametrizables en modelos uniespecíficos.


## 7. Perspectivas evolutivas de la explotación poblacional
Durante la sesión se suscitó el debate sobre las repercusiones a largo plazo que la explotación sostenida imprime sobre los acervos genéticos y la evolución demográfica de las poblaciones explotadas.

Desde la biología evolutiva aplicada a la gestión pesquera y cinegética, someter a una población a una tasa de mortalidad por pesca sostenida durante décadas constituye una de las fuerzas de selección direccional más intensas inducidas por el ser humano, desencadenando transformaciones ecológicas y microevolutivas profundas:

### 6.1. Selección fenotípica artificial y adelanto de la maduración sexual

Los artes de pesca comerciales actúan de forma selectiva sobre las clases de mayor tamaño mediante la luz de malla o el comportamiento de escape. Al elevar drásticamente la mortalidad de los individuos adultos de gran talla, se genera una ventaja adaptativa para aquellos genotipos que exhiben:

* Maduración gonadal a edades más tempranas.
* Menor tamaño corporal en la primera reproducción.
* Menor tasa intrínseca de crecimiento somático post-madurez.

Este fenómeno (denominado *Fisheries-Induced Evolution*, FIE) genera un «reloj evolutivo inverso»: poblaciones históricamente caracterizadas por individuos longevos y fecundos ven reducida de forma estable su talla media y edad de madurez, lo cual deteriora su fecundidad global (relación potencial talla-número de huevos) y su capacidad de resiliencia frente a perturbaciones climáticas.

### 6.2. Erosión de la variabilidad genética y deriva génica

Los episodios de sobrepesca aguda o colapsos poblacionales forzados por la convergencia de eventos ambientales adversos y sobreexplotación (como los observados en las fases de caída demográfica en el Pacífico sudoriental) generan cuellos de botella demográficos periódicos. Estos colapsos conllevan:

* Pérdida de alelos raros por deriva génica estocástica.
* Reducción del tamaño efectivo de la población ($N_e$).
* Disminución del potencial evolutivo y de la plasticidad fenotípica del stock frente al cambio climático y las enfermedades emergentes.


## 8 Conclusión

En esta sesión nos hemos enfrentado por primera vez a algo que condiciona tanto la estructura como el funcionamiento de los sistemas ecológicos: la complejidad. Hemos visto como una herramienta teórica válida (técnicas de explotación de poblaciones biológicas) genera resultados dispares cuando se aplica en la vida real. Esta discrepancia entre las teorías ecológicas y la efectividad de su aplicación se debe, fundamentalmente a dos razones:
- Los conceptos vistos hasta ahora se centran en la ecología de las poblaciones. No contemplan la interacción entre especies, ni la relación de las especies con su medio. Por eso los conceptos como la capacidad de carga no terminan de ser útiles aquí. Cambian mucho en virtud de muchas variables que no estamos considerando. Este punto débil será abordado en las sucesivas sesiones en las que trascenderemos el concepto de población.
- La ecología que estamos estudiando adolece de una visión humana. No contemplamos, hasta ahora, a los seres humanos como piezas clave del funcionamiento del sistema. Esto hace que nuestros modelos mentales no terminen de explicar lo que ocurre en realidad. Este problema será abordado en el segundo cuatrimestre, cuando estudiemos los ecosistemas con la componente humana. Hablaremos entonces de socioecosistemas. 

Los dos puntos débiles anteriores se engloban en uno general. Hasta ahora nuestra mirada es reduccionista. Necesitamos una mirada sistémica para entender mejor la realidad. En los próximos capítulos aprenderemos en qué consiste esto...






****

[Aquí](https://github.com/aprendiendo-cosas/Te_poblaciones_explotacion_ecologia_ccaa/archive/refs/tags/2026_2027.zip) puedes descargar un archivo .zip que contiene este guión en formato html y todo el material que incluye.

****

Haz click [aquí](https://github.com/aprendiendo-cosas/Te_poblaciones_explotacion_ecologia_ccaa/releases) para ver cómo ha cambiado este guión en los distintos cursos académicos.

****

[Aquí](https://github.com/aprendiendo-cosas/Te_poblaciones_explotacion_ecologia_ccaa/blob/2026_2027/notas_imparticion_Te_poblaciones_explotacion_ecologia_ccaa.md) puedes ver las notas que tomó el profesor una vez que se impartió la clase.


****

 <p xmlns:cc="http://creativecommons.org/ns#" >El contenido de este repositorio se puede utilizar bajo la siguiente licencia:  <a  href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1"  target="_blank" rel="license noopener noreferrer"  style="display:inline-block;">CC BY-NC-SA 4.0<img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"  alt=""><img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"  alt=""><img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"  alt=""><img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"  alt=""></a></p> 

<p>Esta licencia no aplica a enlaces a artículos, libros o imágenes no originales. Estos productos tienen su licencia correspondiente.</p>



