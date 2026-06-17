# Modelo de predicción de matrícula — PUCESA

Trabajo de Integración Curricular en Ingeniería en Sistemas de la Información.
Pontificia Universidad Católica del Ecuador Sede Ambato (PUCESA).

**Autor:** Josue Javier Gamboa Cazares
**Director:** Mg. Edison Fernando Meneses Torres
**Año:** 2026

## Descripción
Modelo ensemble (SARIMA + Holt-Winters + Regresión de Huber, combinados
por mediana) para la predicción de matrícula institucional, validado
mediante walk-forward expansivo de 5 periodos (MAPE = 5,93 %) y prueba
ciega contra 2026-P1 (error = 5,31 %).

## Estructura del repositorio
- `Defensa_Tesis_PUCESA_FINAL.ipynb` — Cuaderno reproducible end-to-end.
- `Datos 2015-2020.xlsx` — Serie histórica BANNER (Excel multipestaña).
- `1. Estadísticas Inscritos - CSV 2020.csv` ... `2025.csv` — Reportes BANNER.
- `2. Asignaturas por estudiante_20260423_*.csv` — Archivos 2026-P1.

## Reproducción
1. Clonar el repositorio o abrir el cuaderno en Google Colab.
2. Subir los nueve archivos-fuente al entorno de ejecución.
3. Ejecutar todas las celdas en orden (Runtime → Run all).

## Dependencias
pandas, numpy, openpyxl, statsmodels, scikit-learn, matplotlib.

## Licencia
Uso académico. Los datos provienen del sistema BANNER de la PUCESA y se
publican con fines exclusivos de verificación del Trabajo de Integración
Curricular.
