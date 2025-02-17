# Comparison of K-Means, Hierarchical Clustering, and DBSCAN in data segmentation

## Descripción del proyecto

Proyecto de aprendizaje automático no supervisado enfocado en la aplicación y comparación de algoritmos de clustering. 
El objetivo principal es analizar un conjunto de datos, detectar valores atípicos y generar agrupaciones con distintos enfoques (K-Means, DBSCAN y Clustering Jerárquico) para encontrar el método que mejor se ajuste a la estructura de los datos. 
Se incluyen visualizaciones y métricas de evaluación para respaldar las decisiones tomadas.


## Objetivos
- Exploración de los datos: comprender la estructura, dimensiones y características relevantes del dataset.
- Detección de outliers: identificar y tratar los valores extremos que puedan sesgar la formación de clusters.
- Aplicación de algoritmos de clustering: entrenar K-Means, DBSCAN y Clustering Jerárquico con distintos parámetros.
- Comparación de resultados: usar métricas como Silhouette Score y representaciones gráficas para evaluar la calidad de las agrupaciones.
- Conclusiones: determinar el método más adecuado según el propósito.

## Tecnologías utilizadas
- Python 3.
- Bibliotecas:
  - NumPy, Pandas, Matplotlib, Seaborn para manejo de datos y visualización.
  - scikit-learn para algoritmos de clustering (K-Means, DBSCAN, AgglomerativeClustering).
  - scipy para generación de dendrogramas y análisis estadístico.
- Jupyter Notebook o cualquier IDE que soporte Python.


## Flujo de trabajo

1. Carga y exploración de datos: lectura del dataset, inspección de columnas, valores nulos, tipos de datos, etc
2. Limpieza y tratamiento de outliers: eliminación o imputación de registros atípicos, escalado de variables continuas.
3. Clustering:
   - K-Means: variación del número de clusters (k) y evaluación con Silhouette Score.
   - DBSCAN: ajuste de eps y min_samples para equilibrar densidad y ruido.
   - Clustering Jerárquico: prueba de distintos métodos de enlace (average, complete, ward) y número de clusters.
4. Evaluación:
   - Cálculo del Silhouette Score y análisis cualitativo de la separación.
   - Visualización en 2D usando PCA y/o dendrogramas.
5. Conclusiones: discusión de resultados y selección del método con mejor rendimiento según el contexto.


## Próximas mejoras
- Optimizar el tratamiento de datos categóricos: integrar codificación de variables categóricas si es necesario y probar su impacto en la formación de clusters.
- Aplicar otras técnicas de reducción de dimensionalidad, como t-SNE o UMAP, para una visualización diferente.
- Realizar un proceso de búsqueda automatizada (Grid Search o Random Search) más exhaustivo en los hiperparámetros de DBSCAN y Clustering Jerárquico.
- Incluir validación cruzada y más métricas de evaluación (por ejemplo, Davies-Bouldin Index) para comprobar la robustez de los clusters.
- Integrar análisis de los clusters en el dominio específico del dataset, por ejemplo, etiquetar cada cluster con características relevantes para la toma de decisiones.


