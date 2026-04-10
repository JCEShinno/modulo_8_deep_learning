# Proyecto Módulo 8 - Fundamentos de Deep Learning

## Descripción
Proyecto de Deep Learning aplicado a la clasificación de imágenes de ropa. El objetivo consiste en automatizar la categorización de productos en una tienda virtual, utilizando redes neuronales artificiales y convolutivas sobre el dataset Fashion-MNIST.

## Objetivo
Diseñar, entrenar e implementar un modelo capaz de clasificar imágenes de prendas de vestir en sus respectivas categorías, comparando una red neuronal densa con una red neuronal convolutiva (CNN), y justificando la selección del modelo final.

## Tecnologías utilizadas
- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Pillow

## Estructura del proyecto
- `data/`: archivos del proyecto si corresponde
- `notebooks/`: notebook principal del desarrollo
- `outputs/`: gráficos de entrenamiento, predicción y comparación
- `external_images/`: imágenes externas para pruebas manuales
- `docs/`: informe final técnico
- `README.md`: descripción general del repositorio

## Desarrollo del proyecto
El notebook principal se organiza en cuatro etapas:

1. La red neuronal artificial  
2. Deep Learning  
3. Implementación de redes neuronales en Python  
4. Redes neuronales convolutivas  

## Modelos implementados
- Red neuronal densa binaria
- Red neuronal densa multiclase
- Red neuronal convolutiva (CNN) multiclase

## Dataset utilizado
Se utilizó el dataset **Fashion-MNIST**, compuesto por imágenes en escala de grises de 28x28 píxeles distribuidas en 10 categorías de ropa y accesorios:
- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot

## Principales hallazgos
- La red densa binaria logró muy buen desempeño en una tarea simple de dos clases.
- La red densa multiclase funcionó como baseline para el problema completo.
- La CNN multiclase superó al modelo denso en clasificación de imágenes.
- La arquitectura convolutiva fue más adecuada para preservar la estructura espacial de las imágenes.
- Las predicciones sobre imágenes externas mostraron que el modelo funciona razonablemente bien, aunque con limitaciones fuera de la distribución del dataset.

## Resultados finales
Comparación final entre modelos en el conjunto de prueba:
- **CNN multiclase**: test_loss = 0.2502 | test_accuracy = 0.9095
- **Red densa multiclase**: test_loss = 0.3253 | test_accuracy = 0.8823

## Archivos principales
- `notebooks/proyecto_modulo_8_deep_learning.ipynb`
- `outputs/leccion1_curvas_entrenamiento_binario.png`
- `outputs/leccion1_predicciones_binarias.png`
- `outputs/leccion2_ejemplos_por_clase.png`
- `outputs/leccion3_curvas_mejor_modelo_denso.png`
- `outputs/leccion3_predicciones_multiclase_denso.png`
- `outputs/leccion4_curvas_cnn.png`
- `outputs/leccion4_matriz_confusion_cnn.png`
- `outputs/leccion4_predicciones_cnn_test.png`
- `outputs/leccion4_predicciones_imagenes_externas.png`
- `docs/Proyecto Módulo 8 Clasificador inteligente de imágenes de ropa.pdf`

## Conclusión
El proyecto permitió implementar y comparar arquitecturas de Deep Learning para clasificación de imágenes de ropa. La CNN fue seleccionada como modelo final por lograr mejor desempeño que la red densa multiclase, confirmando que una arquitectura convolutiva resulta más adecuada para este tipo de problema.

## Autor
Juan Carlos Castro Encina
