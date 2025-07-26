# Análisis de Sistemas Planetarios Usando Python

Este repositorio contiene el análisis físico y orbital de cuatro sistemas planetarios reales, realizado con Python como parte del curso *Física del Universo* (ITAM, 2025). El estudio se basa en datos públicos y software libre como `lightkurve` y `radvel`, trabajando directamente sobre curvas de luz y simulaciones keplerianas.

Autores: Mariana Arroyo y Uriel Sagahon

---

## 📄 Ensayo Final

El documento completo del proyecto, con introducción teórica, metodología, resultados y conclusiones, está disponible en el siguiente archivo PDF:

📘 [Análisis de Sistemas Planetarios (PDF)](./Análisis%20de%20Sistemas%20Planetarios.pdf)

---

## 🛠 Herramientas Utilizadas

- [Lightkurve](https://docs.lightkurve.org/): para descarga, limpieza y análisis de curvas de luz astronómicas.
- [Radvel](https://radvel.readthedocs.io/): para ajuste de velocidades radiales usando modelos keplerianos.
- Python, Jupyter Notebooks, NumPy, Matplotlib, Pandas.

---

## 🌌 Sistemas Analizados

Todos los resultados (códigos, cálculos, visualizaciones, curvas de luz y diagramas orbitales) están documentados en los siguientes notebooks:

| Sistema      | Descripción breve                                           | Notebook |
|--------------|-------------------------------------------------------------|----------|
| **Kepler-10**  | Primer planeta rocoso confirmado fuera del Sistema Solar   | [Abrir](./Kepler-10.ipynb) |
| **Kepler-9**   | Sistema con 3 planetas y resonancia orbital                | [Abrir](./Kepler-9.ipynb) |
| **Kepler-419** | Sistema con excentricidad extrema (e ≈ 0.83)               | [Abrir](./Kepler-419.ipynb) |
| **HD 156668**  | Sistema con planeta de muy baja masa, detectado por RV     | [Abrir](./HD156668.ipynb) |

---

## 🎥 Presentación del Proyecto

Puedes visualizar nuestra presentación interactiva (con video) desarrollada en Canva, aquí:

▶️ [Ver presentación en Canva](https://www.canva.com/design/DAGt13VPQ3o/Wwz4CQCLdmznDXnXPBp8EA/edit?utm_content=DAGt13VPQ3o&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

---

## ⚙️ Requisitos Técnicos

Para ejecutar los notebooks, recomendamos crear un entorno virtual e instalar las dependencias necesarias con:

```bash
pip install lightkurve radvel numpy matplotlib pandas
