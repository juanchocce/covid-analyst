# 📊 Análisis de COVID-19 en Perú (2020-2022)

Este proyecto es un análisis integral de la evolución de la pandemia de COVID-19 en el Perú, abarcando el periodo crítico de **2020 a 2022**. Utilizando datos abiertos del Ministerio de Salud (MINSA), el objetivo fue transformar datos crudos en información visual estratégica para entender el impacto de los contagios y fallecimientos a nivel nacional.

<img width="1366" height="768" alt="1" src="https://github.com/juanchocce/covid-analyst/blob/main/covid%201.jpg" />

## 🚀 Tecnologías Utilizadas

Para este proyecto se implementó un flujo de trabajo de datos (ETL) completo:

* **SQL Server:** Motor de base de datos utilizado para el almacenamiento, limpieza y transformación de los archivos CSV masivos. 🗄️
* **Power BI:** Herramienta principal para el modelado de datos y la creación de dashboards interactivos. 📈
* **CSV / Open Data:** Fuente de datos cruda proveniente de la plataforma de datos abiertos del MINSA. 📄

## 🛠️ Proceso de Desarrollo

1.  **Extracción y Carga:** Importación de grandes volúmenes de datos (registros de infectados y fallecidos) a SQL Server.
2.  **Limpieza de Datos (Data Cleaning):** Estandarización de nombres de provincias, distritos y departamentos. Manejo de valores nulos y filtrado por rangos de fechas (2020-2022).
3.  **Modelado:** Creación de un modelo de estrella en Power BI, relacionando tablas de hechos (Infectados/Fallecidos) con dimensiones de tiempo y geografía.
4.  **Visualización:** Diseño de un dashboard intuitivo que permite filtrar por ubicación, género y edad.

## 📌 Características Principales del Dashboard

* **Mapa Interactivo:** Visualización de infectados por distrito en todo el mapa del Perú. 🗺️
* **Análisis Demográfico:** Pirámides de edad para comparar la vulnerabilidad entre hombres y mujeres. 👥
* **Evolución Temporal:** Gráficos de líneas que muestran las "olas" de contagios y decesos a lo largo del tiempo. 🌊
* **KPIs Clave:** Contadores totales de infectados (4M+) y fallecidos (115K+) con actualización dinámica.

## 📂 Estructura del Repositorio

* `/SQL_Scripts`: Consultas utilizadas para la limpieza y segmentación de datos.
* `/Dashboard`: Archivo `.pbix` de Power BI.
* `/Data`: Referencias a las fuentes de datos originales.

## 👤 Autor

**Juan Chocce** - *Ingeniero de Sistemas*
* LinkedIn: [Juan Chocce](https://www.linkedin.com/in/juanchocce/)
* GitHub: [@juanchocce](https://github.com/juanchocce)

---
Proyecto desarrollado con fines educativos y de análisis de datos. 🇵🇪
