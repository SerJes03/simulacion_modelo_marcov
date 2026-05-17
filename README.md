# Modelo Oculto de Markov (HMM) - Diagnóstico Médico

[cite_start]Este repositorio contiene la implementación de un Modelo Oculto de Markov diseñado para inferir el estado de salud de un paciente (Saludable, Resfriado, Gripe) a partir de observaciones de temperatura corporal. [cite: 15, 26, 31]

## 📋 Contenido
- [cite_start]**Código Fuente:** Implementación en Python con interfaz interactiva. [cite: 53, 57]
- [cite_start]**Documentación:** Informe detallado del modelo y matrices. 
- [cite_start]**Evidencias:** Gráficas de Viterbi y tablas de convergencia. [cite: 96, 102]

## 🚀 Instrucciones de Ejecución
1. **Opción Google Colab (Recomendada):** - Sube el archivo `.ipynb` a Colab.
   - Ejecuta todas las celdas (`Ctrl + F9`).
   - [cite_start]Usa los sliders para ajustar los días y presiona "Ejecutar Simulación". [cite: 94, 95]
2. **Ejecución Local:**
   - [cite_start]Instala las dependencias: `pip install numpy pandas matplotlib ipywidgets`. [cite: 54, 55, 56]
   - Ejecuta el script: `python src/nombre_del_archivo.py`.

## 📊 Modelo Matemático
- [cite_start]**Estados Ocultos:** Saludable, Resfriado, Gripe. [cite: 25]
- [cite_start]**Observaciones:** Temperatura Normal, Fiebre Leve, Fiebre Alta. [cite: 30]
- [cite_start]**Algoritmo de Viterbi:** Utilizado para la inferencia de estados con alta precisión diagnóstica. [cite: 67, 88]

## 📈 Resultados y Evidencias
El modelo demuestra estabilidad estadística mediante un análisis de convergencia. [cite_start]Se determinó que a partir de las **57 simulaciones**, el error respecto a la distribución estacionaria teórica cae por debajo del 0.5%. [cite: 92, 104]

![Gráfica de Convergencia](results/grafica_convergencia.png)
