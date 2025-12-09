# Modelamiento Hidráulico – Ecualizador PTAS EAPSA Melipilla  
### Enero–Septiembre 2025  
**Autor:** Yeray Squicciarini Gatica  

Este repositorio contiene el modelamiento hidráulico completo del ecualizador de la Planta de Tratamiento de Aguas Servidas (PTAS) EAPSA Melipilla.  
El proyecto incluye la limpieza y reconstrucción del afluente, la simulación dinámica del volumen del estanque y el análisis de un controlador proporcional del caudal de salida.

---

## 📂 Contenido del repositorio

### 📘 /notebooks
- **CodigoEAPSA.ipynb**  
  Notebook principal con:
  - Preprocesamiento de datos
  - Limpieza hidráulica
  - Reconstrucción científica de gaps
  - Balance de volumen del ecualizador
  - Control proporcional de Q_out
  - Simulación base y análisis del escenario +20%

### 🖼️ /figuras
Todas las figuras generadas por el notebook:
- heatmap_diario.png  
- perfil_promedio_horario_comparacion_mensual.png  
- boxplot_Q_in_dia_semana.png  
- hist_Q_in_por_mes.png  
- volumen_ecualizador.png  
- Q_in_vs_volumen.png  
- Q_in_vs_Q_out.png  
- monthly_summary_simulacion.png  
- curva_controlador.png  
- Figuras del escenario +20%

### 📊 /tablas
Tablas generadas automáticamente:
- tabla_calidad.csv  
- tabla_estadisticas_mensuales.csv  
- tabla_metodos.csv  
- tabla_gap.csv  
- tabla_dias_criticos.csv  
- monthly_summary_simulacion.csv  

### 📑 /datos
- Excel maestro del afluente:  
  `EAPSA_Caudal_Afluente_Enero-Septiembre_2025.xlsx`

---

## 🧪 Requisitos
- Python 3.9+
- Jupyter Notebook
- Pandas, NumPy, Matplotlib

---

## 🎯 Objetivo
Evaluar la estabilidad hidráulica del ecualizador de la PTAS EAPSA Melipilla mediante:
- análisis del afluente real,
- simulación dinámica del volumen,
- implementación de un control proporcional,
- análisis de escenarios con aumento de caudal.

---

## 📄 Licencia
Repositorio académico. Uso exclusivo para fines educativos y de evaluación.
