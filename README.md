# Dataset de Imágenes Modificadas - 180x180

## Descripción

Este conjunto de datos contiene imágenes que han sido procesadas y modificadas para tener un tamaño uniforme de 180x180 píxeles. Las imágenes han sido renombradas secuencialmente de acuerdo a su orden en la carpeta, con nombres en el formato `filtro1.jpg`, `filtro2.jpg`, ..., `filtroN.jpg`, donde `N` es el número total de imágenes en el conjunto de datos.

Este dataset está destinado a tareas de procesamiento de imágenes, entrenamiento de modelos de visión por computadora y otros proyectos relacionados con análisis de imágenes.

## Estructura del Dataset

La carpeta contiene archivos de imagen con las siguientes características:

- **Formato de archivo**: `.jpg` o `.jpeg`
- **Tamaño de cada imagen**: 180x180 píxeles
- **Cantidad de imágenes**: [Número total de imágenes en el conjunto de datos]
- **Nombres de los archivos**: Las imágenes están renombradas secuencialmente en el formato `filtro1.jpg`, `filtro2.jpg`, ..., `filtroN.jpg`.

## Propósito

El dataset puede ser utilizado para los siguientes fines:

- Entrenamiento de modelos de clasificación de imágenes
- Entrenamiento de modelos de detección de objetos
- Pruebas de modelos de segmentación de imágenes
- Otros proyectos de visión por computadora

## Instrucciones de Uso

1. **Acceso al Dataset**: Descargue el conjunto de datos desde el repositorio o acceda al archivo comprimido que contiene las imágenes procesadas.
2. **Formato de las imágenes**: Las imágenes están en formato `.jpg` o `.jpeg` y tienen un tamaño uniforme de 180x180 píxeles.
3. **Procesamiento y Carga**: Para cargar las imágenes en su entorno de trabajo, puede utilizar bibliotecas como `Pillow` o `OpenCV` en Python.

   Ejemplo de carga con `Pillow`:
   ```python
   from PIL import Image

   # Cargar una imagen
   imagen = Image.open('ruta/a/la/imagen/filtro1.jpg')

   # Mostrar la imagen
   imagen.show()



# Licencia
Este conjunto de datos está disponible para uso no comercial y personal. No se permite la redistribución o uso comercial sin el permiso explícito del creador del conjunto de datos.
