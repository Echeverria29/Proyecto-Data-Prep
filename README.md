# Proyecto de Limpieza de Datos con Data Prep

Este proyecto utiliza Google Cloud Data Prep para buscar y limpiar datasets almacenados en Cloud Storage. La herramienta permite realizar procesos de limpieza de datos de manera eficiente, eliminando duplicados, valores nulos y estandarizando los datos para su posterior análisis.

![](images/dataprep.png)

## Contenido
- [Requisitos](#requisitos)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Instrucciones de Ejecución](#instrucciones-de-ejecución)

---

## Requisitos

Para ejecutar este proyecto, necesitas:

- **Acceso a Google Cloud Platform (GCP)**: Con permisos para acceder a Cloud Storage y Data Prep.
- **Google Cloud Data Prep**: Herramienta para la preparación y limpieza de datos.
- **Python**: Para ejecutar scripts adicionales relacionados con la limpieza de datos.

Asegúrate de tener configurado el entorno de GCP y acceso a los buckets de Cloud Storage.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

- **files/**
  Contiene archivos relacionados con el proyecto:
  - `webscraping.rar` - Archivos descargados desde el proceso de scraping.

- **images/**
  Contiene imágenes del proyecto:
  - `dataprep.png` - Ejemplo de limpieza de datos en Data Prep.

- **scripts/**
  Scripts Python del proyecto:
  - `limpieza_datos.py` - Script para realizar limpieza de datos adicional a través de Python.

## Instrucciones de Ejecución

### Limpieza de Datos en Data Prep

1. Accede a Google Cloud Data Prep desde tu cuenta de GCP.
2. Conecta Data Prep a tu bucket de Cloud Storage donde se encuentran los datasets.
3. Carga el dataset y aplica las siguientes transformaciones:
   - Eliminar valores duplicados.
   - Rellenar o eliminar valores nulos.
   - Estandarizar formatos de datos (fechas, números, etc.).
4. Guarda el dataset limpio en un nuevo bucket de Cloud Storage.

### Limpieza Adicional con Python

1. Descarga los archivos procesados desde Data Prep.
2. Coloca los archivos en la carpeta `files/` del proyecto.
3. Ejecuta el script `limpieza_datos.py` para realizar una limpieza adicional:
   ```bash
   python scripts/limpieza_datos.py
   ```
4. Los datos finales se guardarán en la misma carpeta `files/` con un sufijo indicando que han sido procesados.

---
