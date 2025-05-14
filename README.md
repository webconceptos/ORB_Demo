# 🧠 ORB Feature Detection & SLAM Simulation

Este repositorio contiene una demostración completa del detector de características **ORB (Oriented FAST and Rotated BRIEF)** y una simulación visual de un sistema tipo **SLAM (Simultaneous Localization and Mapping)**.

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/webconceptos/ORB_Demo/blob/main/ORB_Demo_Completo.ipynb)

---

## 📚 Contenido

- `ORB_Demo_Completo.ipynb`: Notebook principal con todas las pruebas y visualizaciones.
- `SLAM_robot_simulacion_flecha_fija.gif`: GIF animado que simula el movimiento de un robot detectando keypoints y trazando su trayectoria.
- Imágenes base para pruebas:
  - `edificio.jpg`
  - `edificio_rotado.jpg`
  - `paisaje1.jpg`, `paisaje2.jpg`
  - `frame_*.jpg`: frames simulados de desplazamiento
  - `match_frame_*.jpg`: emparejamiento entre frames consecutivos

---

## 🧪 Pipeline del Proyecto

1. **🟢 Detección de puntos clave**
2. **🔷 Cálculo de descriptores**
3. **🔁 Emparejamiento entre imágenes**
4. **📐 Estimación de transformaciones (homografía)**
5. **🧵 Stitching panorámico**
6. **🤖 Simulación de SLAM visual con animación**

---

## 🧠 ¿Qué es ORB?

ORB es un algoritmo eficiente que combina:
- `FAST`: detección rápida de esquinas
- `BRIEF`: descriptores binarios compactos
- Mejora con **invarianza a rotación** y escala mediante análisis de orientación

---

## 📈 Comparación de rendimiento

ORB es hasta **10 veces más rápido que SIFT**, aunque ligeramente menos robusto en condiciones complejas. Ideal para aplicaciones en tiempo real como:
- SLAM visual
- Drones y robótica móvil
- Realidad aumentada
- Dispositivos con hardware limitado

---

## 🎥 Vista previa del sistema SLAM

![Simulación SLAM](SLAM_robot_simulacion_flecha_fija.gif)

---

## 🚀 Cómo ejecutar en Google Colab

1. Sube los archivos a tu Google Drive o clona el repositorio.
2. Abre el notebook en Colab usando el botón o este [enlace directo](https://colab.research.google.com/github/webconceptos/ORB_Demo/blob/main/ORB_Demo_Completo.ipynb).
3. Ejecuta celda por celda. Asegúrate de subir las imágenes si no están cargadas.

---

## ✨ Créditos

Este trabajo fue desarrollado como parte de una práctica avanzada de visión por computador, enfocada en demostrar la utilidad real de los detectores de características y su integración en sistemas visuales como SLAM.
