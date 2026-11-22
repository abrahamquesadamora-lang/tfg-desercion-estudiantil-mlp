# Prueba de concepto: MLP para clasificación retrospectiva del abandono estudiantil

Repositorio de **código para consulta académica** correspondiente al Trabajo Final de Graduación (Universidad Nacional, Costa Rica).

## Contenido

| Archivo | Función |
|---|---|
| `notebooks/01_preprocesamiento.ipynb` | Preparación y partición de registros, imputación, escalado y One-Hot Encoding. |
| `notebooks/02_entrenamiento_mlp_v1.ipynb` | Entrenamiento y evaluación de la configuración base V1. |
| `notebooks/03_entrenamiento_mlp_v2.ipynb` | Evaluación de la variante V2, incluida Focal Loss y revisión de umbrales. |
| `notebooks/04_validacion_cruzada_5fold_v1_v2.ipynb` | Comparación CV-5 de V1 y V2, con preprocesamiento reajustado dentro de cada fold. |
| `notebooks/05_medicion_latencia_mlp_v1.ipynb` | Medición de tiempos de inferencia de un modelo V1 previamente guardado. |

## Disponibilidad de datos y artefactos

**Este repositorio no contiene datos institucionales, datasets derivados, modelos `.keras` ni salidas de ejecución.** Los notebooks están disponibles para **consulta del código**, pero no son ejecutables de principio a fin sin que quien los utilice proporcione datos y artefactos autorizados con un esquema compatible. Las rutas que en el entorno de investigación apuntaban a carpetas privadas fueron sustituidas por rutas de ejemplo (`data/` y `outputs/`). El repositorio no promete reproducir métricas publicadas sin los datos originales.

La columna objetivo `y` se separa de las características antes de entrenar y evaluar. La comparación V1–V2, la validación cruzada y el cronometraje pertenecen a etapas experimentales distintas, por lo que sus resultados deben atribuirse a la ejecución correcta.

## Advertencia de privacidad

La publicación del código no constituye autorización para divulgar los datos o los metadatos restringidos suministrados a los investigadores. **Antes de convertir el repositorio en público, confirma que la publicación de los nombres y definiciones de variables y las reglas de procesamiento respeta las condiciones de uso acordadas con la fuente de los datos.**

## Alcance

Prueba de concepto de clasificación *retrospectiva* sobre una muestra histórica. No constituye una implementación institucional de alertas tempranas ni valida la fecha futura de abandono.
