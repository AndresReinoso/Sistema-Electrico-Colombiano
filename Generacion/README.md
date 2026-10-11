# El Sistema de Generación Colombiano: Transición y Descentralización del SIN

Este repositorio presenta un análisis exploratorio y estructurado sobre la evolución, capacidad actual y dinámica de expansión del parque de generación del Sistema Interconectado Nacional (SIN) de Colombia, abarcando proyectos en operación y en etapa de construcción.

El análisis utiliza datos oficiales e infraestructurales (UPME, XM y SUI) procesados mediante cuadernos de Python (notebooks), garantizando trazabilidad de origen y marcas temporales de extracción para evaluar las transformaciones tecnológicas y territoriales de la matriz eléctrica.
<hr/>

<br/>

## Análisis del Sistema de Generación en Colombia : 

![title-banner](https://github.com/AndresReinoso/Sistema-Electrico-Colombiano/blob/main/Generacion/Contenido/SIN.png)

La distribución espacial del SIN refleja un marcado contraste geográfico: la generación hidroeléctrica sostiene el suministro en el interior andino, mientras que los desarrollos solares fotovoltaicos e infraestructura térmica de respaldo presentan un clúster de alta densidad en la Costa Caribe. Esta configuración evidencia el inicio de una transición energética descentralizada fuera del eje andino tradicional.

## 1. Evolución Histórica de la Matriz y Capacidad Instalada
El SIN ha superado los 25,109 MW de Capacidad Efectiva Neta. Históricamente sustentado en hidroelectricidad y respaldo térmico, el parque muestra hoy una creciente diversificación tecnológica.


![title-banner](https://github.com/AndresReinoso/Sistema-Electrico-Colombiano/blob/main/Generacion/Contenido/Distribuci%C3%B3n%20por%20tecnolog%C3%ADa.png)

<br/>

La matriz eléctrica colombiana mantuvo un crecimiento paulatino dominado casi exclusivamente por las grandes centrales hídricas y térmicas durante más de cinco décadas. No obstante, a partir de la presente década, la incursión de tecnologías renovables no convencionales (FNCER) comienza a desplazar marginalmente el perfil de expansión acumulada.

![title-banner](https://github.com/AndresReinoso/Sistema-Electrico-Colombiano/blob/main/Generacion/Contenido/Incremento%20Proyectos.png)

Entre 1900 y 2020 la incorporación de plantas ocurría de forma discreta y espaciada en el tiempo. Desde 2021, la cantidad de proyectos que entran en operación anualmente se ha multiplicado exponencialmente, registrando un récord histórico en el número absoluto de activaciones durante el período reciente.

![title-banner](https://github.com/AndresReinoso/Sistema-Electrico-Colombiano/blob/main/Generacion/Contenido/Capacidad%20Neta%20por%20a%C3%B1o.png)

<br/>

A pesar del volumen alto de proyectos recientes, la capacidad neta agregada anualmente muestra variaciones drásticas. El pico alcanzado en 2022 representa el punto de inflexión más alto de entrada en operación de infraestructura de gran escala en la historia reciente del país.

![title-banner](https://github.com/AndresReinoso/Sistema-Electrico-Colombiano/blob/main/Generacion/Contenido/Nuevos%20proyectos.png)

Mientras que los ciclos de expansión previos (1980–2015) dependían de alternancias entre hidroeléctricas de gran embalse y térmicas a gas/carbón, el flujo de proyectos incorporados en el trienio reciente está masivamente dominado por la tecnología solar fotovoltaica.

![title-banner](https://github.com/AndresReinoso/Sistema-Electrico-Colombiano/blob/main/Generacion/Contenido/Declive%20Capacidad%20por%20planta.png)
<br/>

Existe una tendencia clara de fragmentación del parque de generación: mientras el siglo XX se caracterizó por megaproyectos individuales de cientos o miles de megavatios, los nuevos desarrollos corresponden a parques solares o autogeneradores de escala pequeña y mediana (menores a 20-50 MW promedio). Esto introduce nuevos retos operativos para el Centro Nacional de Despacho (CND) en términos de gestionabilidad y control de frecuencia.

![title-banner](https://github.com/AndresReinoso/Sistema-Electrico-Colombiano/blob/main/Generacion/Contenido/Generacion%20por%20departamento.png)

<br/>

Antioquia, Cundinamarca y Atlántico concentran casi el 50% de la Capacidad Efectiva Neta del país. Antioquia mantiene un liderazgo histórico indiscutible debido al aprovechamiento hídrico de sus cuencas.

<br/>


![title-banner](https://github.com/AndresReinoso/Sistema-Electrico-Colombiano/blob/main/Generacion/Contenido/Lideres%20en%20Proyectos%20Nuevos.png)

Al aislar la capacidad incorporada en los últimos años, la geografía de la generación cambia radicalmente: Atlántico, Bolívar y Cesar lideran la nueva capacidad, impulsados por elevados niveles de irradiancia solar. Departamentos tradicionalmente hidroeléctricos como Antioquia muestran aportes marginales en la nueva capacidad neta instalada durante este período.
<br/>

Puedes revisar el desarrollo completo en el siguiente enlace: [Ver Notebook de Análisis](Análisis%20Sistema%20de%20Generación%20en%20Colombia.ipynb)

Ahora, parte de las preguntas resultantes del análisis presentado en esté notebook, incluía revisar si efectivamente los nuevos proyectos en construcción o adjudicación mantenían este fuerte componente de generación solar. Para resolver este interrogante, revisamos rápidamente la documentación existente, especificamente el informe registros activos de proyectos de generación eléctrica, disponible en la UPME. Este se descargo a la fecha de corte de Agosto 30/2026, pero es un archivo de actualización mensual, por lo cual debe consultarse continuamente. 

Este archivo contiene datos valiosos de los proyectos en construcción, su ubicación y la tecnología y recurso empleados. 

![title-banner](https://github.com/AndresReinoso/Sistema-Electrico-Colombiano/blob/main/Generacion/Contenido/Pipeline%20Proyectos%202027-2033.png)

Con base en el mismo, se identifica que la tendencia se mantiene, el pipeline de proyectos en construcción muestra la predominancia de la tecnología Solar, y sorpresivamente la inclusión de proyectos Eólicos, y algunos proyectos hídricos a filo de agua.
El SIN espera integrar cerca de 2600MW adicionales en 2029, registrando para este periodo un nuevo record de construcción de plantas en el histórico año a año.

![title-banner](https://github.com/AndresReinoso/Sistema-Electrico-Colombiano/blob/main/Generacion/Contenido/Capacidad%20en%20Construccion.png)

Al analizar la capacidad adicional, también notamos que se mantiene la tendencia descentralizadora, en el periodo (2027-2033) los grandes participantes son Cordoba, Cesar y Huila, aportando cerca del 50% de la nueva producción.

![title-banner](https://github.com/AndresReinoso/Sistema-Electrico-Colombiano/blob/main/Generacion/Contenido/MapaNueva%20Capacidad%20Generacion.png)

Puedes revisar el desarrollo completo en el siguiente enlace: [Ver Notebook de Análisis](https://github.com/AndresReinoso/Sistema-Electrico-Colombiano/blob/main/Generacion/Registro%20Activos%20Proyectos%20Generaci%C3%B3n%20-%20Ago%202026.ipynb)

> **Nota:** Para finalizar, es importante señalar que algunas de las funcionalidades interactivas (particularmente en los mapas generados) pueden no renderizarse de forma directa en la visualización estática del repositorio. Sin embargo, puedes clonar o descargar el repositorio, y ejecutar localmente el *notebook* para garantizar su correcta visualización interactiva.
