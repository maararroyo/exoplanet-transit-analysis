# exoplanet-transit-analysis

Este repositorio contiene el análisis de tránsitos de sistemas planetarios (**HD 156668, Kepler-10, Kepler-9, Kepler-419**) usando `lightkurve`, `radvel` y fórmulas de astrofísica para estimar parámetros estelares y orbitales sin depender del NASA Exoplanet Archive.

También se incluyen visualizaciones de arquitectura orbital generadas con `matplotlib`.

Este proyecto fue desarrollado como parte de la materia *Física del Universo* (ITAM, verano 2025).

Autores: Mariana Arroyo y Uriel Sagahon

---

##  Ensayo

El documento completo con introducción teórica, resultados y conclusiones se encuentra aquí:



---

## Herramientas usadas

- [Lightkurve](https://docs.lightkurve.org/): descarga, limpieza y análisis de curvas de luz.
- [Radvel](https://radvel.readthedocs.io/): ajuste de modelos keplerianos de velocidad radial.
- Python, NumPy, Matplotlib, JupyterLab.

---

## Sistemas Analizados

### 1. Kepler-10

Estrella tipo G, 2 planetas confirmados. Primer planeta rocoso validado por tránsito.

[Notebook del análisis](notebooks/Kepler-10.ipynb)

---

### 2. Kepler-9

Sistema resonante con 3 planetas, detectados por tránsito.

[Notebook del análisis](notebooks/Kepler-9.ipynb)

---

### 3. Kepler-419
![Excentricidad extrema](figures/arquitectura_kepler419.png)

Sistema con fuerte excentricidad (e ≈ 0.83) detectada por velocidad radial.

[Notebook del análisis](notebooks/kepler-419.ipynb)

---

### 4. HD 156668

Sistema con un planeta de masa muy baja, detectado vía velocidad radial.

[Notebook del análisis](notebooks/HD156668.ipynb)

---

## Requisitos

Instala las dependencias con:

```bash
pip install -r requirements.txt
