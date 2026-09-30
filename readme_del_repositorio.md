# Herramientas Estadísticas e Informáticas para la Gestión Energética

> **Especialización en Eficiencia Energética** — Universidad Santo Tomás (USTA)

Repositorio que reúne los cuadernos de trabajo, ejemplos y ejercicios del curso, enfocados en el uso de **Python**, **estadística aplicada** y **análisis de datos** para resolver problemas reales del sector energético.

La idea central es combinar teoría estadística con aplicaciones prácticas en ingeniería, trabajando con datos energéticos, meteorológicos y de comportamiento de sistemas.

---

## 🎯 Objetivo general

Al finalizar el curso, el estudiante será capaz de:

- Comprender conceptos estadísticos básicos y su interpretación en contextos de ingeniería.
- Trabajar con datos reales y series temporales.
- Usar Python para explorar, visualizar y analizar información.
- Modelar escenarios y tomar decisiones apoyadas en evidencia cuantitativa.
- Aplicar herramientas de análisis a problemáticas de energía y recursos naturales.

---

## 📁 Estructura del repositorio

```text
.
├── Clase_1/                          # Análisis de irradiancia solar
│   └── 01_ejemplo_irradiancia.ipynb
├── Clase_2/                          # Estadística aplicada a ingeniería
│   ├── 01_Estadistica.ipynb          # Estadística descriptiva
│   ├── 02_escenarios_viento_estadistica.ipynb  # Simulación de escenarios
│   └── 03_reto_1.ipynb               # Reto: patrones temporales
├── Clase_3/                          # Material complementario
├── Clase_5/                          # Material complementario
├── HerramientasEstadisticas.xlsx     # Plan del curso y documentación
└── README.md
```

---

## 📚 Contenido por clase

### Clase 1 — Análisis de irradiancia solar
* **Archivo:** `Clase_1/01_ejemplo_irradiancia.ipynb`
* **Caso de estudio real:** Evaluar el comportamiento del recurso solar en una ubicación determinada usando datos de irradiancia solar horaria.
* **Temas principales:**
  - Obtención de datos desde una API pública (`requests`).
  - Transformación de JSON a DataFrames con `pandas`.
  - Limpieza y preparación de series temporales.
  - Análisis de irradiancia global horizontal (GHI).
  - Agrupación por mes para identificar períodos óptimos y críticos.
  - Visualización con `matplotlib`.
* **Aprendizajes clave:** Conectar Python con fuentes de datos abiertas, convertir información cruda en tablas analizables y usar estadística descriptiva para interpretar recursos energéticos.

### Clase 2 — Estadística para ingeniería

#### 2.1 `01_Estadistica.ipynb`
* Introduce la estadística como herramienta para responder preguntas sobre sistemas reales.
* Media, mediana, rango y desviación estándar.
* Análisis de dispersión y estabilidad.
* Comparación entre conjuntos con igual promedio pero comportamiento distinto.
* Generación de datos simulados con distribución normal.
* Histogramas y visualización de frecuencia.

#### 2.2 `02_escenarios_viento_estadistica.ipynb`
* Visión aplicada de simulación de escenarios para recursos variables como el viento.
* Variable aleatoria, PDF y CDF.
* Percentiles y estadística condicionada.
* Patrones de viento por hora y mes.
* Simulación de Monte Carlo.
* Modelado probabilístico de variables continuas.

#### 2.3 `03_reto_1.ipynb`
* **Reto aplicado:** Exploración de patrones temporales en un sistema de bicicletas públicas.
* Diferencias por hora del día.
* Comparación entre semana vs. fin de semana.
* Detección de patrones mensuales.
* Uso de `groupby`, gráficos de barras, histogramas y comparaciones temporales.

---

## 🛠️ Entorno de trabajo

El proyecto se desarrolla en Python con las siguientes bibliotecas:

* **pandas:** Manipulación y análisis de DataFrames.
* **numpy:** Cálculo numérico y generación de variables aleatorias.
* **matplotlib:** Visualización y gráficos.
* **scipy:** Distribuciones de probabilidad y funciones estadísticas.
* **requests:** Consulta de APIs públicas de datos.

### Instalación

```bash
# Clonar el repositorio
git clone https://github.com/Carchaloneo22/Herramientas-estad-sticas-e-inform-ticas-para-la-gesti-n-energ-tica.git
cd Herramientas-estad-sticas-e-inform-ticas-para-la-gesti-n-energ-tica

# Crear entorno virtual
python -m venv .venv

# Activar entorno virtual
# En Linux/macOS:
source .venv/bin/activate
# En Windows:
.venv\Scripts\activate

# Instalar dependencias
pip install pandas numpy matplotlib scipy requests jupyter
```

Luego abre los notebooks con:

```bash
jupyter notebook
```

---

## 🗺️ Ruta de aprendizaje sugerida

1. **Clase 1** → Entender el flujo completo de datos energéticos (API → limpieza → análisis → visualización).
2. **`01_Estadistica.ipynb`** → Consolidar fundamentos de estadística descriptiva.
3. **`02_escenarios_viento_estadistica.ipynb`** → Ver la estadística aplicada a simulación probabilística.
4. **`03_reto_1.ipynb`** → Practicar análisis exploratorio y visualización de forma autónoma.

---

## 🔄 Estado del proyecto

Este repositorio se actualiza conforme avanza el curso. Próximas incorporaciones previstas:

- [ ] Nuevos notebooks de clases avanzadas
- [ ] Ejercicios resueltos
- [ ] Proyectos o entregas finales
- [ ] Análisis adicionales por tema

---

## 👤 Autor

**Carlos Chaparro** — Estudiante de Especialización en Eficiencia Energética, USTA.  
*Última actualización: septiembre 2026*