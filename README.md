# 🧠 ORB Feature Detection & SLAM Simulation

Este repositorio contiene una demostración completa del detector de características **ORB (Oriented FAST and Rotated BRIEF)** y una simulación visual de un sistema tipo **SLAM (Simultaneous Localization and Mapping)**.

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

## 🧪 Experimentos incluidos en el Notebook

1. **Visualización de puntos clave con ORB**
2. **Prueba de invarianza a rotación**
3. **Comparación de tiempos entre ORB y SIFT**
4. **Stitching panorámico simple**
5. **Comparación visual con SIFT**
6. **Simulación de SLAM con múltiples frames**
7. **Animación final con flecha roja fija representando la dirección del robot**

---

## 🧠 ¿Qué es ORB?

ORB es una técnica que combina:
- `FAST`: detector rápido de esquinas.
- `BRIEF`: descriptores binarios muy eficientes.
- Mejora con **invarianza a rotación y escala**.

Ideal para aplicaciones **en tiempo real**, como:
- Robótica
- SLAM
- Visión móvil

---

## 🚀 Cómo ejecutar en Google Colab

1. Sube este repositorio o ZIP a tu Google Drive.
2. Monta tu Drive en Colab:
```python
from google.colab import drive
drive.mount('/content/drive')
```
3. Descomprime el ZIP:
```bash
!unzip "/content/drive/MyDrive/ORB_Demo_SLAM_Final.zip" -d "/content/orb_demo"
```
4. Abre el notebook:
```bash
%cd /content/orb_demo
```

---

## 📸 Captura destacada

![Simulación SLAM](SLAM_robot_simulacion_flecha_fija.gif)

---

## ✨ Créditos

Desarrollado como parte de una demostración avanzada del algoritmo ORB, con visualizaciones, simulaciones y explicaciones simples, a solicitud de la docunete Elian del curso de Visión por Computador - III Ciclo de la Mestría en Inteligenci Artificial
Integrantes del Grupo:
1. Aradiel Hilario
2. Estacio Deiby
3. García Fernando
4. Meza Moises.

