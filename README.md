# 🏥 Diagnóstico Médico mediante Modelo Oculto de Markov (HMM)

[cite_start]Este repositorio contiene la implementación de una simulación estocástica para inferir el estado de salud de un paciente basándose en síntomas visibles[cite: 15].

## 📋 Descripción del Proyecto
[cite_start]El objetivo es aplicar el conocimiento de **Modelos Ocultos de Markov** para modelar la evolución de un paciente a través de tres estados reales: **Saludable, Resfriado y Gripe**[cite: 24, 25].

## 🛠️ Tecnologías y Librerías
Este proyecto utiliza:
* [cite_start]**NumPy:** Cálculos probabilísticos y matrices de transición/emisión[cite: 54].
* [cite_start]**Pandas:** Gestión de tablas de resultados[cite: 55].
* [cite_start]**Matplotlib:** Generación de gráficas de evolución y convergencia[cite: 56].
* [cite_start]**ipywidgets:** Interfaz interactiva para el usuario[cite: 57].

## 📊 Resultados Clave
1. [cite_start]**Algoritmo de Viterbi:** Logra determinar la secuencia de salud más probable con alta precisión diagnóstica[cite: 68, 88].
2. [cite_start]**Convergencia Estacionaria:** Se validó que, al aumentar el número de simulaciones, el error disminuye drásticamente, convergiendo a la distribución teórica esperada[cite: 92, 114].
3. [cite_start]**Punto de Estabilidad:** La simulación demuestra que a partir de las **57 simulaciones**, el sistema alcanza estabilidad estadística (Error < 0.5%)[cite: 103].

## 🚀 Cómo Ejecutar
1. Instalar dependencias: `pip install -r requirements.txt`.
2. Abrir `simulacionmarcov.ipynb` en Google Colab o Jupyter Notebook.
3. Ejecutar todas las celdas para activar los controles interactivos.

---
[cite_start]**Autor:** Jessica Serna Vargas [cite: 4]
[cite_start]**Institución:** IU Digital de Antioquia [cite: 8]


