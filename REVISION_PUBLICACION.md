# Informe de preparación de notebooks para GitHub

**Resultado:** cinco notebooks principales localizados y revisados. Copias generadas sin outputs, sin contadores de ejecución y sin metadatos privados de Colab.

| Archivo público | Celdas | Salidas eliminadas | Original |
|---|---:|---:|---|
| `01_preprocesamiento.ipynb` | 16 | 0 | `Preprocesamiento_Base_Depurada_Red_Neuronal(2).ipynb` |
| `02_entrenamiento_mlp_v1.ipynb` | 49 | 25 | `red_neuronal_test1_resultados_preliminares_consolidado(1).ipynb` |
| `03_entrenamiento_mlp_v2.ipynb` | 45 | 31 | `MLP_Desercion_V2_experimental_validado(2).ipynb` |
| `04_validacion_cruzada_5fold_v1_v2.ipynb` | 36 | 17 | `Validacion_Cruzada_5Fold_V1_V2(1).ipynb` |
| `05_medicion_latencia_mlp_v1.ipynb` | 11 | 10 | `Medicion_Tiempo_Respuesta_MLP_V1.ipynb` |

**Total de bloques de salida eliminados:** 83.

## Intervenciones efectuadas

- Se conservaron las celdas de explicación y los algoritmos de preparación, entrenamiento, CV-5 y latencia.
- Se retiraron las salidas de ejecución y los metadatos no esenciales.
- Se sustituyeron rutas personales de Google Drive y se desactivó su montaje automático.
- Se retiraron del cuaderno de latencia las métricas originales hardcodeadas de una ejecución distinta, manteniendo la explicación metodológica.
- Se normalizaron nombres y referencias de carpetas sin incorporar archivos privados.
- Se comprobaron estructura nbformat y sintaxis estática de todas las celdas Python.

## Limitaciones y aprobación antes de publicar

- No se reejecutaron los notebooks (no se distribuyen los datos originales).
- La inspección estática ayuda a detectar rutas y secretos conocidos, pero no certifica por sí sola que el esquema de datos, los nombres de atributos o el código puedan divulgarse sin autorización.
- El cuaderno exploratorio `ACP_PCA_en_Colab (1).ipynb` también está disponible, pero no está incluido en este paquete de cinco notebooks centrales.

## Integridad

Las copias públicas fueron generadas desde los originales sin modificarlos. SHA-256 de cada archivo público:

- `01_preprocesamiento.ipynb`: `a907ca481694f57b54d2096e90dcd43b79cf2ec4faf7c20657034967581aff17`
- `02_entrenamiento_mlp_v1.ipynb`: `1e220ab451b2519ed55ba99c9c0c603da47306f111d302042c9e4137473baffe`
- `03_entrenamiento_mlp_v2.ipynb`: `9561f32ce61e8355c4a96abfef6533c4d1ae59164a6d705bb45d7c7ace2de117`
- `04_validacion_cruzada_5fold_v1_v2.ipynb`: `f6ded96ec398146e07e423ab1bb56eeed3dcaece4969646496278c608e527076`
- `05_medicion_latencia_mlp_v1.ipynb`: `ff5a67ba5f283b10d58325a8492ddebb8605f05bfd85ae1b757a08da594672c3`
