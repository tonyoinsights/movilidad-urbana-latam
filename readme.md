# Análisis de Movilidad Urbana y Productividad Económica en LATAM 🚗📈

## 📝 Descripción del Proyecto
Este proyecto busca evaluar la relación entre la congestión vehicular y el desempeño económico en las principales ciudades de Latinoamérica. Como analista, el objetivo fue identificar patrones que ayuden a priorizar inversiones en infraestructura de transporte basándose en datos reales.

Se utilizaron datasets de:
* **TomTom Traffic Index:** Datos de congestión y tiempos de viaje.
* **OECD Cities:** Indicadores económicos y demográficos.

## 🎯 Objetivos Clave
1.  **Limpieza y Consolidación:** Unificar datasets heterogéneos mediante técnicas de *Multi-merge*.
2.  **Análisis Estadístico:** Calcular la correlación entre el PIB per cápita y los índices de tráfico.
3.  **Identificación de Insights:** Determinar qué ciudades presentan mayores ineficiencias operativas debido al tráfico.

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python
* **Librerías:** Pandas (Manipulación de datos), Matplotlib & Seaborn (Visualización estadística).
* **Entorno:** Jupyter Notebook.

## 📊 Resultados Principales
* **Correlación:** Se halló un coeficiente de correlación de **$r = 0.28$**. Aunque es una correlación débil-moderada, sugiere que ciudades con mayor PIB tienden a enfrentar mayores retos de movilidad, pero no de forma lineal, lo que indica otros factores estructurales en juego.
* **Calidad de Datos:** Se realizó un proceso exhaustivo de manejo de valores nulos y estandarización de nombres de ciudades para asegurar la integridad del análisis.

## 📁 Estructura de Archivos
* `S5 ladb_mobility_economy_project_student.ipynb`: Notebook principal con todo el proceso de ETL y análisis.
* `analisis_trafico_economia_2024.csv`: Dataset final limpio y procesado.

---
**Contacto:** Antonio Castillo - [LinkedIn](https://www.linkedin.com/in/tonyoinsights/)
