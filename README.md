# Machine Learning Project

## Objetivos
Aplicación de una red neuronal convolucional para la detección de defectos en latas de comida

## Fuentes
Las imágenes han sido obtenidas del sitio web [**Roboflow**](https://roboflow.com/)
- **Título**: canned-food-surface-defect Dataset
- **Tipo**: Open Source Dataset
- **Autor**: Canned Food Surface Defect Classification
- **Publicado en**: [Roboflow Universe](https://universe.roboflow.com/canned-food-surface-defect-classification/canned-food-surface-defect)
- **Editorial**: Roboflow
- **Año**: 2022
- **Visita**: Última visita realizada el 2024-03-23

Este conjunto de datos contiene información sobre defectos en la superficie de alimentos enlatados. Puedes encontrar más detalles y acceder al conjunto de datos en el enlace proporcionado.

## Datos
La clasificación se realiza sobre 8.095 imágenes, pero debido al gran tamaño del conjunto de todas las imágenes sólo se ha dejado una muestra representativa de ellas ubicada en el directorio *data/sample_can_defects* del repositorio. La organización de las imágenes de muestra se ha realizado en tres conjuntos:
- train: X imágenes
- valid: X imágenes
- test: X imágenes

El conjunto original de imágenes ha sido almacenado en un directorio local y están organizadas de la siguiente forma:
- train: 5.658 imágenes
- valid: 1.609 imágenes
- test: 828 imágenes 

Las imágenes muestran distintos tipos de latas fotografiadas desde diferentes ángulos y distancias (con vistas frontal y superior). La defectología del conjunto de latas se ha clasificado en:
- no_defect
- minor_defect
- major_defect
- critical_defect 


