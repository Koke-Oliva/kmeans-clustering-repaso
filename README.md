# K-means Clustering - Repaso

Este proyecto contiene un repaso detallado del algoritmo de **K-means Clustering** utilizando datos simulados. Se trata de un ejercicio de aprendizaje práctico para explorar el comportamiento del algoritmo y mejorar la comprensión de la segmentación de datos. El proyecto está implementado en Python usando **Jupyter Notebook**.

## 🔢 Índice de Contenidos
1. Generación de datos aleatorios
2. Visualización de los datos
3. Aplicación del algoritmo K-means
4. Método del Codo
5. Distancia intra-cluster
6. Métricas de validación
7. Gráfica comparativa de índices de validación
8. Análisis predictivo
9. Análisis de la varianza intra-cluster
10. Librerías utilizadas

## Descripción del Proyecto
El objetivo de este proyecto es realizar un repaso práctico sobre el uso del algoritmo de **K-means** para segmentar datos generados aleatoriamente. A lo largo del notebook se exploran distintas etapas del proceso de clustering, desde la generación de los datos hasta la evaluación de la calidad de los clusters formados.

### 1. Generación de Datos Aleatorios
Los datos se generaron de manera aleatoria usando `numpy`, con el objetivo de tener cuatro grupos definidos. Esto permite un mejor control sobre los datos y facilita la interpretación de los resultados del clustering.

### 2. Visualización de los Datos
Se utilizó `matplotlib` y `seaborn` para visualizar los datos generados, lo cual facilitó la comprensión de su distribución antes de aplicar el algoritmo.

### 3. Aplicación del Algoritmo K-means
El algoritmo de K-means se implementó utilizando `scikit-learn`. Se probaron diferentes valores para el número de clusters con el objetivo de identificar el mejor ajuste para los datos.

### 4. Método del Codo
El **método del codo** se utilizó para determinar el número óptimo de clusters. Se calculó la suma de errores cuadráticos (SSE) para diferentes cantidades de clusters y se generó una gráfica que permite visualizar el punto de inflexión.

### 5. Distancia Intra-cluster
Se calculó la **distancia intra-cluster** para evaluar la compacidad de los clusters formados, un método importante para entender qué tan cercanos están los puntos dentro de un mismo cluster.

### 6. Métricas de Validación
Se aplicaron diferentes métricas de validación para medir la calidad de los clusters, como el **coeficiente de silueta**. Además, se generó una gráfica comparativa para analizar los índices obtenidos.

### 7. Análisis Predictivo
Una vez definidos los clusters, se realizó un **análisis predictivo** usando los resultados del modelo para asignar nuevas muestras a los clusters formados.

### 8. Análisis de la Varianza Intra-cluster
Se evaluó la varianza intra-cluster para comprobar la homogeneidad de los datos dentro de cada cluster.

## Tecnologías Utilizadas
- **Python** con **Jupyter Notebook**
- **Pandas** y **NumPy** para la manipulación de datos
- **Scikit-learn** para aplicar el algoritmo K-means
- **Matplotlib** y **Seaborn** para la visualización de datos

## Cómo Ejecutar el Proyecto
1. Clona este repositorio:
   ```sh
   git clone https://github.com/Koke-Oliva/kmeans-clustering-repaso.git
   ```
2. Asegúrate de tener instaladas las librerías necesarias. Puedes instalarlas ejecutando:
   ```sh
   pip install -r requirements.txt
   ```
3. Abre el archivo `.ipynb` en **Jupyter Notebook** y sigue los pasos descritos.

## Resultados
Los resultados incluyen visualizaciones de los clusters y evaluaciones detalladas de la calidad de los mismos. Estos resultados ayudan a comprender mejor la agrupación lograda por el algoritmo y cómo se relacionan los datos entre sí.

## Próximos Pasos
- Aplicar estas técnicas a un conjunto de datos más complejo y real.
- Utilizar otros algoritmos de clustering para comparar resultados.

## Contacto
Si deseas más información o tienes alguna duda, no dudes en contactarme a través de [mi perfil de GitHub](https://github.com/Koke-Oliva).

