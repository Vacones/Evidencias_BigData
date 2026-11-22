# Evidencia individual — Jacob Espejel Guiza

**Matrícula:** A01712021 · **Módulo 6: Big Data**

[Notebook de la evidencia](https://github.com/Vacones/Evidencias_BigData/blob/main/Individual/A01712021/A01712021_Jacob%20Espejel%20Guiza_Evidencia.ipynb) · [Google Colab](https://colab.research.google.com/drive/1UN2_JtPT-s6vtRF6u6VITHAAnNA61-rm) · [Dashboard Tableau Public](https://public.tableau.com/app/profile/jacob.espejel/viz/Libro4_17940038331000/SMOKEResultados)

El proyecto estima el área de cajas de humo en imágenes con PySpark y MLlib. Utiliza un dataset original de 3.118 GB, un Pipeline de Random Forest seleccionado mediante cross validation de tres folds y evaluación sobre 4,294 imágenes de prueba.

El notebook contiene explicación del problema, preparación y calidad de los datos, procesamiento por particiones, exploración, entrenamiento, métricas, predicciones, gráficas y captura del dashboard. Las salidas científicas conservadas corresponden a la ejecución del 6 de noviembre de 2026.

Resultados finales: MAE 9.75 pp, RMSE 15.43 pp, R² 0.4733 y reducción relativa de RMSE de 27.43% frente al promedio de entrenamiento. La carpeta `resultados` conserva tablas, registros y gráficas de esa ejecución; las imágenes originales se consultan en la fuente Kaggle enlazada en el notebook.

La captura publicada conserva dos rótulos diferentes de la evaluación con CV (RMSE y R²); el notebook identifica la diferencia y utiliza las métricas originales de Spark. Los archivos JSON se mantienen como registros de la sesión, por lo que pueden referenciar la publicación inicial del dashboard.
