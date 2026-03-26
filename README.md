<div align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">
  
  # <H1> Análisis de la Depresión Juvenil </H1>  
  [![InfluxDB](https://img.shields.io/badge/InfluxDB-TSDB-22ADF6?style=flat-square&logo=influxdb&logoColor=white)](https://www.influxdata.com/)
  [![Grafana](https://img.shields.io/badge/Grafana-Dashboard-F46800?style=flat-square&logo=grafana&logoColor=white)](https://grafana.com/)
  [![Power BI](https://img.shields.io/badge/Power_BI-Analytics-F2C811?style=flat-square&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
  [![Linux](https://img.shields.io/badge/OS-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://kernel.org)

  [![SQL](https://img.shields.io/badge/SQL-Querying-CC2927?style=flat-square&logo=mysql&logoColor=white)](https://en.wikipedia.org/wiki/SQL)
  [![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
  [![Excel](https://img.shields.io/badge/Excel-Data_Analysis-217346?style=flat-square&logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/excel)
</div>

---
## Introducción
En este proyecto abarcaremos el tema de la depresión en los jovenes. El aumento de la prevalencia de este tipo de trastornos exige que empezemos a usar nuevas herramientas que sirvan para analizar y prevenir estos casos, superando metodos actuales. 

Vamos a hacer una aplicación de la ciencia de datos para analizar la prevalencia de la depresión en los adolescentes. Utilizando datos demográficos y encuentas de salud mental, el objetivo será transformar registros estáticos (los hallados en los datos y encuestas) en un sistema de monitoreo en tiempo real. A través de la integración de Python, SQL y herramientas de visualización, esto nos permitirá identificar varios patrones que no se hayan analizado antes, correlacionar variables distintas y avisar alertas tempranas para las decisiones preventivas en cuanto a salud mental. 

---
<br>

## 📂 Contenido del Repositorio
<br>

> 📁 [Datos](https://github.com/MACR-prog/Taller-05/tree/main/Datos): Archivos de Excel e InfluxDB  
---
> 📁 [Gráficas](https://github.com/MACR-prog/Taller-05/tree/main/graficas): Contenido visual  
---
> 📁 [Análisis](https://github.com/MACR-prog/Taller-05/tree/main/Analisis): Documentos con conclusiones y hallazgos  
---
<br>

## Desarrollo del Proyecto
El proceso de desarrollo se dividió en cuatro fases:

### 1. Adquisición de datos 
![](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white) ![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

La investigación comenzó con la recopilación de datos demográficos y encuestas de salud mental en jóvenes.
*  **Origen:** Se utilizaron archivos `.xlsx` y `.csv`.
*  **Limpieza:** Mediante scripts de **Python** se realizó la limpieza de datos para eliminar duplicados y así normalizar las variables.

---

### 2. Almacenamiento de datos 
![](https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=influxdb&logoColor=white) ![](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

*  **Base de Datos:** Se configuró un servidor en **Ubuntu Linux** para alojar a InfluxDB.
*  **Procesos:** Se hizo uso de **SQL** para cargar las variables recolectadas y enlazarlas con la base de datos y grafana.

---

### 3. Análisis de Datos 
![](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=microsoft-power-bi&logoColor=black)

*  Se crearon modelos relacionales para identificar la correlación entre los datos recolectados.
*  Se hizo estudio de gráficas.

---

### 4. Visualización 
![](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white) ![](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=microsoft-power-bi&logoColor=black)

Para la visualización y gráficas se utilizó Grafana y Power BI:
*  **Dashboards:** Paneles interactivos que muestran picos y tendencias con la depresión en los jóvenes.
*  **Alertas:** Configuración de umbrales visuales para detectar grupos de riesgo en los datos analizados.

---
<br>

## Visualizaciones Clave
<div align="center">
  <table style="width:100%">
    <tr>
      <td width="33%">
        <p align="center"><b>Distribución de Depresión</b></p>
        <img src="https://raw.githubusercontent.com/MACR-prog/Taller-05/main/Distribucion.jpg" width="300">
      </td>
      <td width="33%">
        <p align="center"><b>Mapa de Correlaciones</b></p>
        <img src="https://raw.githubusercontent.com/MACR-prog/Taller-05/main/heatmap.png" width="300">
      </td>
      <td width="33%">
        <p align="center"><b>Promedio depresión segun actividad física</b></p>
        <img src="https://github.com/MACR-prog/Taller-05/blob/main/Promedio%20depresi%C3%B3n.jpg" width="300">
      </td>
    </tr>
  </table>
</div>

---

