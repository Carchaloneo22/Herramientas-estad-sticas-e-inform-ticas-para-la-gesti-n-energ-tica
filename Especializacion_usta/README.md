# Herramientas estadísticas e informáticas para la gestión energética

Este repositorio reúne los cuadernos de trabajo, ejemplos y ejercicios de la especialización en eficiencia energética, enfocados en el uso de Python, estadística aplicada y análisis de datos para problemas del sector energético.

La idea principal es combinar teoría estadística con aplicaciones reales en ingeniería, usando datos energéticos, meteorológicos y de comportamiento de sistemas.

> Este README se actualiza conforme avanza el curso y se incorporan nuevas clases o retos.

## Objetivo general

El curso busca que el estudiante pueda:

- comprender conceptos estadísticos básicos y su interpretación en ingeniería;
- trabajar con datos reales y series temporales;
- usar Python para explorar, visualizar y analizar información;
- modelar escenarios y tomar decisiones apoyadas en evidencia cuantitativa;
- aplicar herramientas de análisis para resolver problemas de energía y recursos naturales.

## Estructura del repositorio

- `Clase 1/`: introducción a la explotación de datos energéticos y análisis de irradiancia solar.
- `Clase 2/`: estadística aplicada, simulación, distribución de variables y reto de análisis de patrones temporales.
- `HerramientasEstadisticas.xlsx`: material de referencia del plan del curso y documentación institucional del espacio académico.

## Clase 1: análisis de irradiancia solar

Archivo principal:

- `Clase 1/01_ejemplo_irradiancia.ipynb`

### ¿De qué trata?

En esta primera clase se trabaja con un caso de estudio real: evaluar el comportamiento del recurso solar en una ubicación determinada, usando datos de irradiancia solar horaria.

### Temas principales

- obtención de datos desde una API pública;
- uso de Python para consultar información meteorológica;
- transformación de datos JSON a DataFrames con Pandas;
- limpieza y preparación de series temporales;
- análisis de irradiancia global horizontal (GHI);
- agrupación por mes para identificar el mejor y peor período solar;
- visualización de resultados con matplotlib;
- respuesta a preguntas de negocio usando datos y gráficos.

### Aprendizajes clave

- cómo conectar Python con fuentes de datos abiertas;
- cómo convertir información cruda en una tabla analizable;
- cómo resumir comportamiento temporal para responder preguntas prácticas;
- cómo usar la estadística descriptiva para interpretar recursos energéticos.

## Clase 2: estadística para ingeniería

Archivos principales:

- `Clase 2/01_Estadistica.ipynb`
- `Clase 2/02_escenarios_viento_estadistica.ipynb`
- `Clase 2/03_reto_1.ipynb`

### 2.1 `01_Estadistica.ipynb`

Esta parte introduce la estadística como una herramienta para responder preguntas sobre sistemas reales, no solo para calcular números.

#### Conceptos trabajados

- media o promedio;
- mediana;
- rango;
- desviación estándar;
- análisis de dispersión y estabilidad;
- comparación entre datos con mismo promedio pero comportamiento distinto;
- generación de datos simulados con distribución normal;
- histogramas y visualización de frecuencia.

#### Propósito pedagógico

Se busca que el estudiante entienda que la estadística no es un conjunto de fórmulas aisladas, sino una forma de caracterizar la variabilidad, la incertidumbre y el comportamiento típico de un sistema.

### 2.2 `02_escenarios_viento_estadistica.ipynb`

Este notebook va más allá de la estadística descriptiva y presenta una visión aplicada de simulación de escenarios.

#### Temas principales

- variable aleatoria;
- función de densidad de probabilidad (PDF);
- función de distribución acumulada (CDF);
- percentiles;
- diferencia entre histogramas y distribuciones teóricas;
- patrones de viento en diferentes horas y meses;
- uso de estadística condicionada;
- generación de escenarios de viento;
- simulación de Monte Carlo;
- modelado de variables continuas para entender su comportamiento probabilístico.

#### Enfoque del notebook

La idea central es mostrar cómo conceptos básicos de estadística se convierten en herramientas reales de ingeniería para analizar recursos variables como el viento y construir escenarios futuros.

### 2.3 `03_reto_1.ipynb`

Este archivo corresponde a un reto aplicado donde se exploran patrones temporales de un sistema de bicicletas públicas, usando la misma lógica analítica que se usa con el viento.

#### Objetivo del reto

- analizar si existen diferencias por hora del día;
- comparar comportamiento entre semana y fin de semana;
- detectar patrones por mes;
- usar `groupby`, gráficos de barras, histogramas y comparaciones temporales.

#### Temas del reto

- estadística descriptiva básica del número de viajes por hora;
- análisis del patrón según la hora del día;
- comparación entre días de la semana;
- segmentación entre semana vs. fin de semana;
- interpretación de resultados con base en comportamiento realista de uso;
- cierre con conclusiones escritas.

#### Aprendizaje esperado

El reto ayuda a reforzar el cálculo de promedios, distribución de datos y comparación visual de patrones, una habilidad clave para problemáticas energéticas y de operación de sistemas.

## Recomendaciones de uso

1. iniciar por la clase 1 para entender la aplicación de datos energéticos en un caso real;
2. continuar con `01_Estadistica.ipynb` para consolidar conceptos fundamentales;
3. revisar `02_escenarios_viento_estadistica.ipynb` para ver estadística aplicada a simulación;
4. resolver el reto de `03_reto_1.ipynb` para practicar análisis exploratorio y visualización.

## Entorno de trabajo

Este proyecto se trabaja con Python y bibliotecas como:

- pandas;
- numpy;
- matplotlib;
- scipy;
- requests.

La carpeta `.venv/` del repositorio contiene el entorno virtual del proyecto para ejecutar los notebooks.

## Actualización del contenido

Este repositorio se irá ampliando con nuevas clases y ejercicios conforme se avance en el curso. Las secciones anteriores pueden actualizarse para incluir:

- nuevos notebooks;
- resultados de prácticas;
- ejercicios resueltos;
- análisis adicionales por tema;
- proyectos o entregas finales.

## Conclusión

El repositorio está orientado a desarrollar una visión práctica y analítica del uso de estadísticas e informática aplicada a la gestión energética. A lo largo del curso, los notebooks permiten pasar de la teoría a la interpretación de datos reales, modelado probabilístico y toma de decisiones basada en evidencia.
