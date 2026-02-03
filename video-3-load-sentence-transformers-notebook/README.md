# Video 3: Inferencia en un Solo Batch (Notebook)

## Objetivo
Cargar un modelo de Sentence-Transformers, ejecutar inferencia sobre un pequeño batch de textos
y guardar los embeddings resultantes en disco (`embeddings.npz`).

## Pasos

1. Abrí el notebook:
   ```bash
   jupyter notebook local_embedding_inference.ipynb
   ```

2. Ejecutá cada celda de forma secuencial:

   * Carga del modelo
   * Ejecución de inferencia sobre textos de ejemplo
   * Guardado de los embeddings en `embeddings.npz`
3. Verificá la salida generada:

   ```bash
   ls -lh embeddings.npz
   ```

## Solución de problemas

* **Errores al descargar el modelo**: asegurate de tener conexión a internet o configurá `LOCAL_FILES_ONLY=True`.
* **Problemas de memoria**: reducí el tamaño del batch dentro del notebook.