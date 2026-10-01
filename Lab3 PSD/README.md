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

* `/src`: Contiene los flujogramas de GNU Radio (`.grc`) y los scripts de Python exportados.
* `/data`: Archivos de prueba (imágenes y audios) utilizados como fuentes de información real.
* `/docs`: Contiene el informe técnico detallado en formato PDF, las imágenes extraídas de los sumideros (sinks) y el código fuente en LaTeX.

## Uso y Reproducción

1. Clonar este repositorio:
   ```bash
   git clone [https://github.com/FabianChacon3/lab3-comunicaciones2-psd.git](https://github.com/FabianChacon3/lab3-comunicaciones2-psd.git)