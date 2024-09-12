# ANÁLISIS COMPARATIVO DE LOS ÍNDICES NDSSI Y NSMI CON IMÁGENES LANDSAT-8 EN EL LAGO CHINCHAYCOCHA, JUNÍN, 2023
### COMPARATIVE ANALYSIS OF NDSSI AND NSMI INDICES WITH LANDSAT-8 IMAGERY IN LAKE CHINCHAYCOCHA, JUNÍN, 2023

## Descripción del Proyecto

Este repositorio contiene el código y los archivos necesarios para reproducir el análisis comparativo de los índices **NDSSI** (Índice de Diferencia Normalizada de Sólidos Suspendidos) y **NSMI** (Índice Normalizado de Material en Suspensión) en el Lago Chinchaycocha, Junín, utilizando imágenes **Landsat-8 OLI Collection 2 Level-2**. Este análisis ayuda a entender la calidad del agua en diferentes áreas del lago afectadas por sólidos suspendidos y partículas en suspensión.

## Contenido del Repositorio

El repositorio contiene los siguientes archivos y carpetas:

- `/shapefiles/`: Carpeta con los archivos **SHP** necesarios para la delimitación del área de estudio.
- `/imagenes_satelitales/`: Contiene un archivo `Imagenes_satelitales.md` con las instrucciones para descargar las imágenes Landsat-8 desde EarthExplorer.
- `/codigo/`: Carpeta con el código en **Python** que realiza el procesamiento de las imágenes y el cálculo de los índices NDSSI y NSMI.

## Instrucciones para Reproducir el Análisis

1. **Descarga las imágenes Landsat-8**:
   Sigue las instrucciones detalladas en el archivo [`Imagenes_satelitales.md`](imagenes_satelitales/Imagenes_satelitales.md) para descargar las imágenes de Landsat-8 necesarias para el análisis.

2. **Configura tu entorno Python**:
   Asegúrate de tener instaladas las librerías necesarias. Puedes instalarlas ejecutando:
   ```bash
   pip install rasterio numpy matplotlib pandas
