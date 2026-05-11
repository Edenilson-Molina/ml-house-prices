## Proyecto
Prediccion de precios de casas con un flujo en notebooks y logica reusable en `src/`.

## Estructura
- `notebooks/01_eda.ipynb`: exploracion y visualizacion.
- `notebooks/02_cleaning_features.ipynb`: limpieza, imputacion y preparacion de datos.
- `notebooks/03_modeling_eval.ipynb`: modelado y evaluacion.
- `data/train.csv`: dataset original (raw).
- `data/processed/`: datasets procesados para modelado.
- `reports/metrics/`: metricas guardadas.
- `models/trained/`: modelos entrenados.

## Flujo recomendado
1. Ejecuta `01_eda.ipynb` para entender los datos.
2. Ejecuta `02_cleaning_features.ipynb` para generar `data/processed/`.
3. Ejecuta `03_modeling_eval.ipynb` para entrenar y evaluar modelos base.

## Requisitos
Instala dependencias desde `requirements.txt` y usa el entorno virtual del proyecto.

## Notas de versionado
- `data/processed/`, `reports/metrics/` y `models/trained/` se ignoran en git para mantener el repo liviano y reproducible.
