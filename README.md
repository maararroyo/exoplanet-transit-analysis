# exoplanet-transit-analysis

Este repositorio contiene el análisis de tránsitos de sistemas planetarios (**HD 156668, Kepler-10, Kepler-9, Kepler-419**) usando `lightkurve`, `radvel` y fórmulas de astrofísica para estimar parámetros estelares y orbitales sin depender del NASA Exoplanet Archive.

También se incluyen visualizaciones de arquitectura orbital generadas con `matplotlib`.

Este proyecto fue desarrollado como parte de la materia *Física del Universo* (ITAM, verano 2025).

Autores: Mariana Arroyo y Uriel Sagahon

---

##  Ensayo

El documento completo con introducción teórica, resultados y conclusiones se encuentra aquí:

[Ver PDF del ensayo](ensayo/Proyecto%20Final%20Física.pdf)

---

## Herramientas usadas

- [Lightkurve](https://docs.lightkurve.org/): descarga, limpieza y análisis de curvas de luz.
- [Radvel](https://radvel.readthedocs.io/): ajuste de modelos keplerianos de velocidad radial.
- Python, NumPy, Matplotlib, JupyterLab.

---

## Sistemas Analizados

### 1. Kepler-10
![Arquitectura Kepler-10](figures/arquitectura_kepler10.png)

Estrella tipo G, 2 planetas confirmados. Primer planeta rocoso validado por tránsito.

[Notebook del análisis](notebooks/kepler-10.ipynb)

---

### 2. Kepler-9
![Curva de luz](figures/curva_luz_kepler9.png)

Sistema resonante con 3 planetas, detectados por tránsito.

[Notebook del análisis](notebooks/kepler-9.ipynb)

---

### 3. Kepler-419
![Excentricidad extrema](figures/arquitectura_kepler419.png)

Sistema con fuerte excentricidad (e ≈ 0.83) detectada por velocidad radial.

[Notebook del análisis](notebooks/kepler-419.ipynb)

---

### 4. HD 156668
![Diagrama HR](figures/HR_diagram_HD156668.png)

Sistema con un planeta de masa muy baja, detectado vía velocidad radial.

[Notebook del análisis](notebooks/HD156668.ipynb)

---

## ⚙️ Requisitos

Instala las dependencias con:

```bash
pip install -r requirements.txt
