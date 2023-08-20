# Clasificación de Señales de Tránsito con CNNs

Este repositorio contiene un proyecto de Machine Learning centrado en la clasificación de imágenes de señales de tránsito utilizando Redes Neuronales Convolucionales (CNNs).

## Índice

- [Características Principales](#características-principales)
- [Herramientas y Librerías Utilizadas](#herramientas-y-librerías-utilizadas)
- [Cómo usar](#cómo-usar)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Características Principales

1. **Preprocesamiento de Datos**: 
   - Carga y visualización de conjuntos de datos.
   - Preparación y normalización de imágenes.
   - Codificación one-hot para etiquetas.

2. **Modelado**:
   - Diseño de un modelo CNN basado en la arquitectura LeNet.
   - Modificaciones al modelo con capas de Dropout y BatchNormalization.
   - Entrenamiento con conjuntos de datos y validación.

3. **Evaluación**:
   - Representación gráfica de métricas a lo largo del entrenamiento.
   - Evaluación en conjunto de prueba.
   - Cálculo de F1-Score, Recall y otras métricas.

4. **Técnicas de Balanceo**:
   - Uso de SMOTE para tratar el desbalanceo de clases.
   - Generación de imágenes artificiales con `ImageDataGenerator`.

## Herramientas y Librerías Utilizadas

- **TensorFlow y Keras**: Frameworks principales para la construcción y entrenamiento de modelos de red neuronal.
- **NumPy**: Operaciones numéricas y manipulación de matrices.
- **Matplotlib y Seaborn**: Herramientas de visualización.
- **Imbalanced-learn (imblearn)**: Proporciona técnicas para abordar el desbalanceo de clases.

## Cómo usar

1. Clona este repositorio en tu máquina local.
2. Instala las dependencias mencionadas en "Herramientas y Librerías Utilizadas".
3. Ejecuta el notebook `CNN_LetNet_TRAFFIC.ipynb` en un entorno Jupyter para seguir el proceso completo desde la carga de datos hasta la evaluación del modelo.

## Contribuciones

Las contribuciones son siempre bienvenidas. Si encuentras algún error o tienes sugerencias, por favor abre un Issue o realiza un Pull Request.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.
