## 📡 TELECOM CUSTOMER CHURN PREDICTION

Machine Learning Project

# 📌 Overview

Este proyecto desarrolla un modelo de Machine Learning para predecir la cancelación de clientes (churn) en la empresa de telecomunicaciones Interconnect, con el fin de apoyar estrategias de retención, marketing y toma de decisiones comerciales.
El análisis se basa en datos de contratos, servicios de internet y telefonía, información demográfica y comportamiento de pago de los clientes.

# 🎯 Objectives

Analizar patrones asociados a la cancelación de clientes.
Preparar y consolidar múltiples fuentes de datos.
Entrenar y evaluar modelos de clasificación.
Seleccionar el modelo con mejor desempeño usando AUC-ROC.
Identificar perfiles de clientes con mayor riesgo de churn.

# ⚙️ Tools

Python · Pandas · NumPy · Scikit-learn · XGBoost · LightGBM · Matplotlib · Seaborn · Jupyter Notebook

# 🧪 Methodology

EDA: análisis descriptivo, correlaciones y visualización.
Preprocesamiento: limpieza, One-Hot Encoding, escalado (StandardScaler).
Target: cancel (1 = cancela, 0 = activo).
Split: 70% train / 30% test (stratified).
Métrica principal: AUC-ROC.
Modelos evaluados:
Regresión Logística, Random Forest, Gradient Boosting, KNN, XGBoost.

# 📊 Key Insights (EDA)

Tasa de cancelación ≈ 26%.
Mayor churn en contratos mes a mes.
Clientes con pagos más altos y facturación electrónica cancelan más.
Clientes senior y sin partner presentan mayor riesgo.
No hay diferencias relevantes por género.
Baja adopción de servicios adicionales.

# ✅ Results & Conclusion

Modelo final: XGBoost optimizado.
ROC-AUC: 0.844, superando a Random Forest y Regresión Logística.
El modelo distingue correctamente clientes que cancelan en ~84% de los casos.
Adecuado para implementación en estrategias de retención y segmentación de clientes.
