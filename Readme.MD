## 📊 Análisis de Datos Públicos de Colombia en Databricks

Este proyecto tiene como objetivo la recolección, limpieza, transformación y análisis de dos conjuntos de datos públicos provenientes del portal de datos abiertos del gobierno colombiano.  
Los datos se procesarán y se cargarán en un entorno de **Databricks** para facilitar su análisis y visualización.

## 📂 Datasets a utilizados

1. **SECOP (Sistema Electrónico para la Contratación Pública)**
   - URL: [rpnr-utcd.csv](https://www.datos.gov.co/resource/rpnr-utcd.csv)
   - Descripción: Contiene registros de contratos públicos realizados por entidades estatales en Colombia.

2. **MEN (Ministerio de Educación Nacional)**
   - URL: [nudc-7nev.csv](https://www.datos.gov.co/resource/nudc-7nev.csv)
   - Descripción: Información relacionada con establecimientos educativos oficiales y privados en Colombia.

## ⚙️ Proceso del proyecto

1. **Descarga de datos**
   - Los datasets serán obtenidos usando SODAPI.

2. **Procesamiento y limpieza**
   - Se eliminarán registros incompletos o inconsistentes.
   - Se normalizarán campos clave como fechas y ubicaciones.
   - Se realizarán transformaciones para facilitar el análisis.

3. **Carga a Databricks**
   - Los datos procesados se subirán al entorno de Databricks.
   - Se crearán tablas estructuradas para su consulta mediante SQL o notebooks.

4. **Análisis**
   - Estadísticas descriptivas.
   - Visualizaciones interactivas.
   - Cruce entre datos de contratación y datos educativos.

## 🛠️ Requisitos del proyecto

- Python 3.11+
- Pandas
- PySpark (opcional)
- Databricks CLI o acceso vía navegador
- Jupyter Notebook o entorno similar

## 🎯 Objetivos 

- Explorar la relación entre educación y contratación estatal en distintas regiones de Colombia.
- Identificar patrones, tendencias y posibles zonas de mejora en la inversión pública y cobertura educativa.
