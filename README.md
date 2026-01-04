# walmart-analisis-ventas-kpi-2012
Análisis de ventas semanales de Walmart (2012) enfocado en eficiencia por departamento y contribución al negocio. Incluye limpieza de datos, KPIs clave y visualizaciones para un resumen ejecutivo con enfoque C-F-I.

## Descripción
Proyecto de análisis de datos realizado en el contexto de un bootcamp de Data Analytics.
El objetivo fue construir un resumen ejecutivo de ventas de Walmart (2012) para apoyar la toma de decisiones comerciales relacionadas con presupuesto, inventario y uso del espacio.

## Objetivo
Responder a las siguientes preguntas clave:
* ¿Qué departamentos fueron más eficientes para generar ventas en 2012?
* ¿Qué departamentos aportaron más al negocio y cuáles estuvieron bajo su potencial?

## Tecnologías utilizadas
- **Google Sheets**
  - Limpieza y transformación de datos
  - Cálculo de KPIs
  - Tablas dinámicas
  - Visualizaciones

## Metodología
- **Limpieza de datos:** Se revisaron duplicados y valores nulos, se realizó validación de fechas y consistencia de ventas.
- **Preparación de datos:** Se unieron las tablas transaccionales y tablas de lookup. Se crearon columnas calculadas para KPIs.
- **Análisis y visualización:** Se insertaron tablas dinámicas, gráficos comparativos y dashboard resumen para stakeholders.
- **Comunicación ejecutiva:** Hallazgos presentados bajo el enfoque C-F-I (Context – Finding – Implication).

## Resultados principales
- **Eficiencia por espacio (Ventas/m²):**  
  El promedio general fue **$4.267,55/m²**, con alta concentración en **Despensa y Básicos** y **Comida Fresca**, que presentan la mayor productividad del espacio.  
  Departamentos como **Jardín y Vida al Aire Libre** y **Oficina y Manualidades** mostraron baja eficiencia, evidenciando oportunidades de reasignación de superficie.

- **Aporte al negocio (Participación de ventas):**  
  Tres categorías (**Despensa, Comida Fresca y Artículos del Hogar y Papel**) concentran **más del 50% de las ventas totales**, consolidándose como categorías core.  
  Un **5% de las ventas** se agrupa en “Otro”, lo que sugiere oportunidades de mejora en la clasificación de datos.

- **Estabilidad y riesgo (Volatilidad de ventas):**  
  El comportamiento general fue moderadamente estable (CV promedio **0,72**).  
  **Juguetes** y **Otro** presentan alta volatilidad (CV > 1,0), mientras que **Despensa**, **Comida Fresca** y **Salud y Bienestar** muestran ventas consistentes y predecibles.

## Estructura del proyecto
walmart-analisis-ventas-kpi-2012/

├── README.md

├── walmart_data_2012.xlsx → Dataset completo con análisis

## Dashboard Principal
![Panel Principal](panel_principal.png)

## Análisis de Volatilidad
![Volatilidad 2012](volatilidad_2012.png)


## Cómo ejecutar el proyecto
- Descargar el archivo `walmart_data_2012.xlsx`.
- Revisar la hoja **README** para comprensión del objetivo, definición de KPIs y documentación técnica.
- Explorar las hojas de limpieza y transformación de datos.
- Consultar las tablas dinámicas y visualizaciones.
- Revisar el **Dashboard** para visualizar los KPIs principales
