# Predicción de Recuperación de Oro – Proyecto Zyfra

Proyecto de Data Science para la empresa **Zyfra**, enfocado en predecir la eficiencia de recuperación de oro a partir de datos de procesos industriales.  
El objetivo es construir un modelo robusto que estime las variables objetivo y pueda apoyar decisiones en la optimización del proceso de producción.

## 📊 Descripción
- Análisis exploratorio de datos industriales de concentración de minerales.  
- Verificación de calidad de los datos (columnas ausentes, distribuciones, balance de concentraciones).  
- Comparación de modelos de Machine Learning con validación cruzada por bloques.  
- Evaluación con la métrica **sMAPE** (symmetric Mean Absolute Percentage Error).  

## 🧪 Resultados
- Se identificaron columnas que no deben usarse como features (outputs, cálculos derivados, objetivos).  
- Pruebas estadísticas confirmaron diferencias significativas en algunas distribuciones entre train y test (ej. `feed_size`).  
- **Regresión Lineal** mostró mejor desempeño promedio que Random Forest (menor sMAPE).  
- Se plantean mejoras futuras: aumentar número de folds, probar modelos de boosting (LightGBM/XGBoost) y ajustar hiperparámetros.  

## 🗂 Estructura
- `notebooks/`: notebook principal con análisis y resultados.  
- `data/`: no incluye datos originales; ver instrucciones en `data/README.md`.  
- `requirements.txt`: dependencias mínimas para reproducir.  

## 🔁 Reproducir (opcional)
1. Crear entorno e instalar dependencias:
```bash
python -m venv .venv
.venv\Scripts\activate   # Windows
pip install -r requirements.txt
