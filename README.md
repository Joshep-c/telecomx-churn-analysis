# 🤖 Telecom X — Parte 2: Predicción de Cancelación (Churn)

Desarrollo de modelos predictivos para identificar clientes con mayor probabilidad
de cancelar el servicio en Telecom X.

## 🛠️ Tecnologías
Python, Pandas, Scikit-learn, Imbalanced-learn, Matplotlib, Seaborn

## 📂 Archivos
| Archivo | Descripción |
|---|---|
| `datos_tratados.csv` | Dataset limpio y procesado (output Parte 1) |
| `TelecomX_Parte2.ipynb` | Notebook con el pipeline completo |

## 🔄 Pipeline
- **Preparación**: encoding, balanceo con SMOTE y normalización con StandardScaler
- **Correlación**: matriz de correlación y análisis dirigido por boxplots
- **Modelado**: Regresión Logística y Random Forest
- **Evaluación**: accuracy, precisión, recall, F1-score y matriz de confusión

## 📊 Resultados

| Modelo | Accuracy | Recall (Churn) | F1 (Churn) |
|---|---|---|---|
| Regresión Logística | 77% | **73%** | **63%** |
| Random Forest | 77% | 63% | 59% |

La **Regresión Logística** es el modelo recomendado por su mayor Recall en la detección de abandono.

## 🔍 Variables más Relevantes
`Meses_Contrato`, `Cargos_Mensuales`, `Cargos_Totales`, `Tipo_Contrato_Month-to-month`

## 📂 Datos originales
[TelecomX — Parte 1](https://github.com/Joshep-c/TelecomX_Latam)
