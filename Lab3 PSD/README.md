# Análisis de Densidad Espectral de Potencia (PSD) de Señales Aleatorias en GNU Radio

Este repositorio contiene la implementación práctica, los diagramas de flujo y el análisis matemático correspondientes a la evaluación de la Densidad Espectral de Potencia (PSD) de diversas señales de telecomunicaciones. El proyecto aborda desde señales binarias pseudoaleatorias teóricas hasta el procesamiento de datos del mundo real (imágenes y audio).

Desarrollado como parte de las prácticas de formación en la Universidad Industrial de Santander.

## Objetivos del Proyecto

* Generar y analizar señales binarias aleatorias bipolares de forma rectangular.
* Evaluar el impacto de la variación de Muestras por Símbolo (Sps) en el ancho de banda y la resolución espectral.
* Comprobar empíricamente las propiedades del ruido blanco gaussiano y su efecto al superponerse sobre señales de información.
* Analizar la PSD de fuentes de datos entrópicos reales (archivos `.jpg` y `.wav`).

## Requisitos y Entorno de Ejecución

El proyecto fue desarrollado y validado en el siguiente entorno:

* **Sistema Operativo:** Linux (Ubuntu)
* **Software:** GNU Radio Companion (GRC) v3.10+
* **Dependencias Adicionales:** Python 3.x, NumPy

## Estructura del Proyecto

```text
📦 comunicaciones-II-labs
├── 📁 Lab3_PSD
│   ├── 📁 data                   # Fuentes de información real (ej. rana.jpg, sonido.wav)
│   │   ├── 📁 img                # Capturas de instrumentación (analizadores QT GUI)
│   │   ├── 📁 tex_source         # Código fuente del informe en LaTeX
│   │   └── 📄 Informe_Lab3.pdf   # Documento final compilado
│   └── 📁 src                    # Flujogramas de GNU Radio (.grc) y scripts Python
├── 📄 .gitignore                 # Exclusión de caché de Python, GNU Radio y LaTeX
├── 📄 LICENSE                    # Licencia MIT
└── 📄 README.md                  # Documentación principal
```
