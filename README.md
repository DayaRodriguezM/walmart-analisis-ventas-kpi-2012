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
- Google Sheets  Limpieza y transformación de datos
- Cálculo de KPIs
- Tablas dinámicas
- Visualizaciones

## Metodología
- **Limpieza de datos:** se revisaron duplicados y valores nulos, se realizo validación de fechas y consistencia de ventas.
- **Preparación de datos:** se unieron las tablas transaccionales y tablas de lookup. Se creó de columnas calculadas para KPIs.
- **Análisis y visualización:** se inserto Tablas dinámicas, gráficos comparativos y dashboard resumen para stakeholders.
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

### Archivos del proyecto
├── **walmart-analisis-ventas-kpi-2012→** Dataset original, Data clean y tablas de referencia.

  ├── dashboard → Capturas del dashboard final en Google Sheets


## Cómo ejecutar el proyecto
- Abrir el archivo de Google Sheets incluido en la carpeta /data.
- Revisar la Hoja README para la comprensión del objetivo, definicion de KPIs, Documentación Técnica, Proceso de validación e Insights y recomendaciones ejecutivas  
- Revisar las hojas de limpieza y transformación de datos.
- Explorar las tablas dinámicas y visualizaciones.
- Consultar el dashboard para visualizar los KPIs principales.
