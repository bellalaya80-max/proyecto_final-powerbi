# 📊 Análisis de Salud Pública: Impacto Socioeconómico y Calidad de Vida

## 📖 Descripción del Proyecto
Este proyecto realiza un análisis descriptivo y estadístico sobre los determinantes sociales de la salud utilizando la base de datos del Sistema de Vigilancia de Factores de Riesgo del Comportamiento (BRFSS). El objetivo principal es identificar y demostrar visualmente cómo factores como el nivel de ingresos y la situación laboral afectan directamente los días de mala salud física de la población. Para llevar a cabo este análisis, se procesaron más de 433,000 registros mediante técnicas de limpieza de datos con expresiones DAX y modelado visual interactivo.

## 📁 Estructura del proyecto
```text

├── data/                                # Conjunto de archivos originales en bruto 
│   ├── processed                        # Datos limpios y transformados
├── notebooks                            # Jupyter Notebook (.ipynb) con el código de unificación
├── Proyecto_Final.pbix                  # Archivo .pbix con el reporte interactivo y matriz ejecutiva
└── README.md                            # Descripción y documentación del proyecto

```
## 🛠️ Instalación y Requisitos
- **Python (Pandas/Jupyter):** Utilizado para la limpieza inicial, unión (Merge) de múltiples fuentes de datos y exportación.
- **Power BI Desktop:** Utilizado para el modelado de datos, creación de medidas DAX y diseño del dashboard.
- **Librerías Python:** `pandas`, `numpy`.

## ⚙️ Flujo de Trabajo (Pipeline de Datos)
1. **Unificación (ETL en Python):** Se procesaron los archivos fuente en un entorno de Jupyter Notebook para realizar el tratamiento de nulos y la unión lógica de los datasets, garantizando la integridad de los registros.
2. **Modelado (Power BI):** El dataset resultante se importó a Power BI, donde se aplicaron medidas DAX para normalizar códigos de salud (88, 77, 99) y crear jerarquías de ingresos.
3. **Visualización:** Diseño de un reporte de tres capas (Descriptivo, Analítico y Ejecutivo) con indicadores visuales de alerta (KPIs).

## 📊 Resultados y Conclusiones
- **La "Escalera de la Desigualdad":** Identificamos una correlación inversa drástica entre el nivel de ingresos y la salud física percibida.
- Las poblaciones más vulnerables (ingresos menores a $15,000 anuales) sufren en promedio **10.3 días** de mala salud física al mes.
- En contraste, los sectores de altos ingresos (más de $200,000 anuales) reportan apenas **2.1 días** de afectación mensual.
- El análisis demográfico sugiere una muestra con tendencia al envejecimiento, donde los jubilados y las personas con incapacidad laboral presentan los mayores índices de vulnerabilidad física.
- El análisis concluye que la salud no es exclusivamente un factor biológico, sino un reflejo directo de la estabilidad económica y el poder adquisitivo.
- La unificación de datos permitió observar que esta brecha es consistente en diferentes situaciones laborales y geográficas.

## 🔄 Próximos Pasos
- Cruzar las métricas de salud física con indicadores de salud mental para obtener un panorama integral del paciente.
- Incorporar variables educativas y de estado civil para profundizar en los determinantes sociales.
- Explorar la evolución histórica de estos datos en los últimos 5 años para identificar tendencias de empeoramiento o mejora en la salud pública.

## 🤝 Contribuciones
Las contribuciones son bienvenidas. Si deseas mejorar este proyecto o aportar nuevos enfoques al análisis de datos de salud, por favor abre un pull request o una issue.

## ✒️ Autores
- [Bella Laya]
- [@bellalaya80-max](https://github.com/bellalaya80-max)
