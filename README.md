# AF2 — Introducción al Aprendizaje Máquina

Actividad Fundamental 2 · UANL / FIME · Modelos de aprendizaje supervisado.

## Contenido
- `AF2_Modelos_Aprendizaje_Supervisado.ipynb`: notebook ejecutable en Google Colab.
- `AF2_Introduccion_Aprendizaje_Maquina.pdf` y `.docx`: reporte académico.
- `requirements.txt`: dependencias.
- `Dataset_limpio.csv`: **debe añadirse desde la AF1**; no se incluye porque no se proporcionó.

## Ejecución
1. Abrir el notebook en Google Colab.
2. Subir `Dataset_limpio.csv` generado en AF1 cuando lo solicite la celda de carga.
3. Ejecutar todas las celdas de arriba abajo.
4. Revisar las métricas reales de prueba y descargar las gráficas.
5. Si se publica en GitHub, añadir el dataset solo si se tiene permiso de redistribución y verificar sus condiciones.

## Metodología
Separación 80/20 estratificada, StandardScaler ajustado solo con entrenamiento, red Dense 32→16→1 (ReLU y sigmoid), Adam, binary crossentropy, EarlyStopping y evaluación con AUC, recall, precisión y matriz de confusión.

**Nota:** el documento explica el procedimiento, pero los valores de evaluación quedan pendientes hasta ejecutar el notebook con el CSV real. No se inventan resultados.


## Dataset incluido
`Dataset_limpio.csv` procede de la AF1: 5,109 filas, 18 columnas, 249 casos positivos y 4,860 negativos. El notebook requiere ejecutar las celdas en Google Colab con TensorFlow para generar resultados y gráficas; las métricas no se consideran verificadas hasta su ejecución.
