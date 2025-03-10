 # Análisis de Datos Aplicables al Teorema de Naïve Bayes

Este proyecto utiliza el **Teorema de Naïve Bayes** para predecir el tipo de Pokémon basándose en diversas características como altura, peso, estadísticas de combate y velocidad.

## Objetivo

El objetivo de este análisis es clasificar a los Pokémon en sus respectivos tipos utilizando un modelo de clasificación basado en Naïve Bayes. El modelo es entrenado con un conjunto de datos (Pokedex) y luego evaluado con métricas como precisión, reporte de clasificación y matriz de confusión.

## Librerías Utilizadas

- **Pandas**: Para la manipulación y análisis de datos.
- **NumPy**: Para trabajar con arrays y matrices.
- **Matplotlib** y **Seaborn**: Para visualización estática de datos.
- **Plotly**: Para visualización interactiva de datos.
- **Scikit-learn**: Para el preprocesamiento de datos, creación de modelos y evaluación.

## Pasos Realizados

1. **Carga y Preprocesamiento de Datos**: 
   - El dataset es cargado desde un archivo CSV y se realiza una limpieza básica, como la normalización de los tipos de Pokémon.
   - Se codifican los tipos de Pokémon utilizando `LabelEncoder` para su uso en el modelo.

2. **Entrenamiento del Modelo**: 
   - Se seleccionan las características más relevantes (altura, peso, estadísticas de combate, etc.) y se divide el conjunto de datos en entrenamiento y prueba.
   - Se entrena un modelo de Naïve Bayes utilizando el conjunto de entrenamiento.

3. **Evaluación del Modelo**: 
   - Se predicen los tipos de los Pokémon en el conjunto de prueba y se evalúa el rendimiento utilizando la precisión, el reporte de clasificación y la matriz de confusión.

4. **Visualización**:
   - Se visualiza la matriz de confusión para mostrar cómo el modelo predice las clases en comparación con los valores reales.
   - Se realiza un análisis multivariable con una gráfica 3D interactiva para explorar la relación entre el ataque, defensa y velocidad de los Pokémon.

## Resultados

El modelo de Naïve Bayes obtiene una precisión de `X.XX` (reemplazar con el valor de precisión real) en la predicción de tipos de Pokémon. La matriz de confusión y el reporte de clasificación proporcionan más detalles sobre su rendimiento.

## Requisitos

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- scikit-learn

## realisado por: Miguel Angel Rodriguez Hernadez
