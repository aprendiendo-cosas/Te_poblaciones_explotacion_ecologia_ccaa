# Explotación de poblaciones

> + **_Tipo de material_**: <span style="display: inline-block; font-size: 12px; color: white; background-color: #029BF9; border-radius: 5px; padding: 5px; font-weight: bold;"> Teoría</span> <span style="display: inline-block; font-size: 12px; color: white; background-color: #E68532; border-radius: 5px; padding: 5px; font-weight: bold;"> Aplicación</span>
> + **_Versión_**: 2025-2026
> + **_Asignatura (grado)_**: Ecología (CCAA)
> + **_Autor_**: Curro Bonet-García (fjbonet@uco.es)
> + **Duración**: Aproximadamente 2 sesiones de 1 hora.



![portada](https://raw.githubusercontent.com/aprendiendo-cosas/Te_poblaciones_explotacion_ecologia_ccaa/2025_2026/imagenes/portada.jpg)

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



### Tipología de equilibrios bajo cuota fija:

1. **Cuota excesiva ($H_0 > H_{\text{máx}}$)**:

   La tasa de extracción supera en todo momento la capacidad máxima intrínseca de renovación de la población. Dado que $\frac{dN}{dt} < 0$ para cualquier densidad, la extinción es el resultado determinista inevitable.

2. **Cuota subcrítica ($H_1 < H_{\text{máx}}$)**:

   La recta de cosecha interseca la curva de reclutamiento en dos puntos de equilibrio donde $\frac{dN}{dt} = 0$:

   - **Punto A ($N_A < K/2$, equilibrio inestable)**: Si la población experimenta una perturbación negativa o una sobreextracción puntual que sitúe a $N$ por debajo de $N_A$, la tasa de extracción superará al reclutamiento ($H > dN/dt$), conduciendo a la población a una espiral de declive irreversible hacia la extinción.
   - **Punto B ($N_B > K/2$, equilibrio dinámicamente estable)**: Si la biomasa disminuye ligeramente, la población entra en una zona donde el reclutamiento supera la cuota extraída ($dN/dt > H$), lo que permite su recuperación espontánea hacia $N_B$. Asimismo, este punto opera retirando individuos en un entorno donde se relaja la competencia intraespecífica, asegurando la sostenibilidad a largo plazo.

3. **Cuota tangencial o Máximo Rendimiento Sostenible ($H_2 = H_{\text{MSY}}$)**:

   La extracción coincide con la cima parabólica del reclutamiento ($N = K/2$). En términos teóricos, maximiza el rendimiento económico sostenido. No obstante, **constituye un equilibrio frágil y metaestable**: cualquier fluctuación ambiental adversa desplaza el sistema hacia la izquierda del punto crítico, situándolo en la zona de extinción estocástica sin capacidad intrínseca de retorno.


En [esta](https://github.com/aprendiendo-cosas/Te_poblaciones_explotacion_ecologia_ccaa/raw/2025_2026/presentacion/graficas_explotacion.pptx) presentación se muestra el hilo argumental seguido en el razonamiento anterior. 


En la segunda parte de este acto docente analizamos con detalle algunos ejemplos reales de explotación de poblaciones animales y vegetales. El contenido de esta parte se puede ver en [este](https://github.com/aprendiendo-cosas/Te_poblaciones_explotacion_ecologia_ccaa/raw/2025_2026/presentacion/explotacion_poblaciones.xmind) mapa mental. Dicho mapa se puede ver de forma dinámica a continuación:

<iframe
  src="https://raw.githack.com/aprendiendo-cosas/Te_poblaciones_explotacion_ecologia_ccaa/2025_2026/presentacion/explotacion_poblaciones.html"
  style="width:100%; height:450px;"
></iframe>


****

[Aquí](https://github.com/aprendiendo-cosas/Te_poblaciones_explotacion_ecologia_ccaa/archive/refs/tags/2025_2026.zip) puedes descargar un archivo .zip que contiene este guión en formato html y todo el material que incluye.

****

Haz click [aquí](https://github.com/aprendiendo-cosas/Te_poblaciones_explotacion_ecologia_ccaa/releases) para ver cómo ha cambiado este guión en los distintos cursos académicos.

****

 <p xmlns:cc="http://creativecommons.org/ns#" >El contenido de este repositorio se puede utilizar bajo la siguiente licencia:  <a  href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1"  target="_blank" rel="license noopener noreferrer"  style="display:inline-block;">CC BY-NC-SA 4.0<img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"  alt=""><img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"  alt=""><img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"  alt=""><img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"  alt=""></a></p> 

<p>Esta licencia no aplica a enlaces a artículos, libros o imágenes no originales. Estos productos tienen su licencia correspondiente.</p>



