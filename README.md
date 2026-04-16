# Detección de Ondas Gravitacionales con Redes Neuronales

Este repositorio contiene un framework de experimentación para la generación y detección de señales de ondas gravitacionales inmersas en ruido, utilizando técnicas de procesamiento de señales y Deep Learning.

## Objetivo del Proyecto
El objetivo es simular señales de "chirp" (similares a las producidas por la fusión de agujeros negros binarios) y entrenar una red neuronal capaz de distinguir la señal del ruido de fondo, simulando los desafíos reales de detectores como LIGO.

## Stack Tecnológico
* **Lenguaje:** Python 3.10+
* **Procesamiento de Señal:** `SciPy`, `NumPy`
* **Visualización:** `Matplotlib`
* **Modelado IA:** `TensorFlow` / `Keras`

## Metodología de Simulación
En el notebook `Gravitational_Waves.ipynb` se implementa:
1. **Generación de Señal:** Uso de funciones de barrido de frecuencia (chirps).
2. **Modelado de Ruido:** Simulación de ruido blanco gausiano.
3. **Inyección de Señal:** Superposición de la señal física en el canal de ruido con diferentes amplitudes para probar la sensibilidad.

##  Configuración del Entorno
Para replicar este entorno científico:
```bash
conda activate gravitational_waves_tf
pip install -r requirements.txt
