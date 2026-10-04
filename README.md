# UNIR — Inteligencia Artificial y Sistemas de Trading

Trabajos de la asignatura **Inteligencia Artificial y Sistemas de Trading** (Máster en Bolsa y
Mercados Financieros, UNIR). Cada actividad vive en su propia carpeta con el notebook, las figuras
de resultados y un README con la teoría aplicada y las conclusiones.

## Actividades

### 📊 [Actividad 1 — Regresión OLS: factores macro de Repsol](Actividad_1_Regresion_OLS_Repsol/)
Regresión lineal múltiple para explicar la rentabilidad semanal de Repsol a partir del IBEX35, el
Brent, el EUR/USD, el VIX y los tipos de interés. Incluye diagnóstico completo del modelo:
multicolinealidad (VIF), heterocedasticidad y normalidad de los residuos.

### 🤖 [Actividad 2 — Predicción ML de la dirección semanal de Repsol](Actividad_2_Prediccion_ML_Repsol/)
Clasificación binaria (sube/baja) con 4 modelos (Logística, Árbol, Random Forest, Naive Bayes)
validados con walk-forward. Resultado: AUC ≈ 0.49-0.50 en todos los modelos, en línea con la
hipótesis de mercado eficiente.

### ✈️ [Actividad 3 — Sistema de trading algorítmico sobre IAG](Actividad_3_Trading_Algoritmico_IAG/)
Pipeline completo de trading cuantitativo: feature engineering, etiquetado Triple-Barrier,
modelos (Random Forest / XGBoost) con Purged K-Fold CV, y backtest walk-forward con coste de
transacción y Deflated Sharpe Ratio. Resultado: en el periodo OOS 2023-2025, Buy & Hold bate a los
modelos de ML (Sharpe 1.12 vs. Sharpe negativo).

## Stack técnico

Python · pandas · numpy · yfinance · statsmodels · scikit-learn · XGBoost · matplotlib / seaborn
