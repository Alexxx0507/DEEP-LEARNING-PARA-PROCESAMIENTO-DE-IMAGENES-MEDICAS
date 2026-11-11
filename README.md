# Taller: Deep Learning para Procesamiento de Imágenes Médicas

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)](#)
[![Google Colab](https://img.shields.io/badge/Ejecutar_en-Google_Colab-F9AB00?logo=googlecolab&logoColor=white)](#)
[![Deep Learning](https://img.shields.io/badge/Deep_Learning-U--Net-FF6F00)](#)

##  Resumen del Taller
Este taller teórico-práctico está diseñado para introducir a los participantes en la aplicación de la inteligencia artificial dentro del ámbito médico. A lo largo de dos días, se abordará el ciclo de vida completo del procesamiento de imágenes radiológicas (Radiografías, Tomografías, Resonancias Magnéticas y Ultrasonido): desde la exploración, preprocesamiento y limpieza de los datos, hasta el desarrollo, entrenamiento y evaluación de modelos de **Deep Learning** para tareas de clasificación y segmentación semántica (arquitecturas como U-Net). 

El objetivo es proporcionar las herramientas necesarias para transformar una imagen médica cruda en un conjunto de datos listo para el entrenamiento de algoritmos que asistan en el diagnóstico clínico.

---

##  Instructores

* **Br. Jorge Alejandro Chávez Gómez** 
  *  Correo: *jorgech4vez05@gmail.com*

* **Ing. Ismael Pérez Ruiz**
  *  Correo: *iperez@modelo.edu.mx*
  *  **Módulos:** Día 2 (Segmentación avanzada, métricas y evaluación clínica).

---

##  Temario del Taller

###  Día 1: De la imagen médica al conjunto de datos listo para entrenar
*A cargo de: Jorge Alejandro Chávez Gómez*

**1. Introducción al procesamiento de imágenes médicas**
* ¿Qué es el procesamiento de imágenes médicas?
* Tipos de imágenes médicas: Radiografías, Tomografía Computarizada (CT), Resonancia Magnética (MRI) y Ultrasonido. 
* Especificaciones técnicas: Cómo se forma la imagen en cada equipo y representación de sus características físicas.
* Aplicaciones actuales de la inteligencia artificial en la medicina.

**2. Fundamentos de Deep Learning aplicados a imágenes**
* Conceptos clave: Inteligencia Artificial, Machine Learning y Deep Learning.
* ¿Qué es una red neuronal artificial?
* Redes Neuronales Convolucionales (CNN).
* Capas convolucionales, funciones de activación (Sigmoide, ReLU, etc.) y operaciones de *Pooling*.
* Entrenamiento de redes neuronales: Funciones de pérdida y optimizadores.
* Extracción automática de características.
* Diferencias entre procesamiento tradicional y Deep Learning.

**3. Formatos y preparación de imágenes médicas**
* Lectura y visualización de imágenes (DICOM, NIfTI, PNG, etc.).
* Normalización de intensidades y redimensionamiento.
* Eliminación de ruido y aumento de datos (*Data Augmentation*).
* Organización de bases de datos: Imágenes y etiquetas.

**4.  Práctica 1: Exploración y preprocesamiento**
* Carga de imágenes médicas utilizando Python.
* Visualización gráfica de imágenes con `Matplotlib`.
* Aplicación de técnicas de preprocesamiento (filtros, ecualización).
* Visualización comparativa de imágenes originales y procesadas.
* Construcción y preparación del *dataset* para Deep Learning.

**5.  Práctica 2: Clasificación de imágenes**
* Carga y análisis exploratorio del conjunto de datos.
* Construcción de una red neuronal para clasificación desde cero.
* Programación del script de entrenamiento.
* Evaluación del modelo y explicación de métricas clave (Accuracy, Loss).

---

###  Día 2: Implementación de Deep Learning en imágenes médicas
*Desarrollo, ejecución y evaluación de un modelo de segmentación.*

**1. Segmentación de imágenes médicas con U-Net**
* ¿Qué es la segmentación médica?
* Diferencia fundamental entre segmentación semántica y clasificación (Ejemplo práctico).
* Análisis de arquitecturas avanzadas: U-Net, FPN y DeepLabv3+.
* Conceptos de máscaras de segmentación (Masks) y etiquetas de referencia (*Ground Truth*).
* Aplicaciones clínicas: Identificación de órganos y detección de lesiones o tumores.

**2.  Práctica 3: Implementación de un modelo U-Net**
* Carga del conjunto de datos etiquetado.
* Configuración de la arquitectura del modelo.
* Entrenamiento y ajuste fino (*Fine-tuning*) del modelo.
* Generación de predicciones.
* Visualización de las máscaras generadas.
* Comparación visual entre la segmentación real y la predicha.

**3. Evaluación y Validación del Modelo**
* Construcción de la matriz de confusión.
* Métricas especializadas en segmentación: *Dice Score* e *Intersection over Union* (IoU).
* Interpretación cuantitativa de resultados.
* Identificación de limitaciones y posibles errores (falsos positivos/negativos).

**4. Cierre del Taller**
* Análisis final de los resultados obtenidos.
* Retos y limitaciones para la implementación de estos modelos en entornos clínicos reales.
* Conclusiones generales y sesión de preguntas (Q&A).

---

##  Requisitos y Uso del Repositorio

1. **Entorno de ejecución:** Todas las prácticas se llevarán a cabo en [Google Colab](https://colab.research.google.com/), por lo que no es necesario instalar software local pesado. Solo necesitas una cuenta de Google.
2. **Conocimientos previos:** Nociones básicas de programación en Python.
3. **Librerías utilizadas:** `numpy`, `matplotlib`, `opencv`, `tensorflow` / `pytorch`, `scikit-learn`.

> **Nota:** Para ejecutar las libretas, abre la carpeta `notebooks/` y haz clic en el botón *Open in Colab* que aparece al inicio de cada archivo.
