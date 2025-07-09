# Explorador EIRA — Zonificación Racional Fractal

Este repositorio implementa el **Método EIRA**  
(Explorador de Islas Racionales Algebraicamente Filtradas) para investigar la **Conjetura de Zonificación Racional Fractal**.

## ✅ Descripción
- Filtra la factibilidad racional de cuerpos algebraicos de grado `n`.
- Usa discriminante inverso para encontrar la **banda crítica viva**.
- Resuelve nodos reales con resolución numérica (`nroots()`).
- Visualiza islotes algebraicos y mide su **estructura fractal** (`D_H`).

## 📈 Contenido del notebook
- `EIRA_Zonificacion_Fractal.ipynb`: flujo completo EIRA con:
  - Familia polinómica paramétrica.
  - Gráfica de banda crítica.
  - Nodos reales (islotes).
  - Box-counting para estimar dimensión fractal.

## ⚙️ Requisitos
- Python 3.x
- `sympy`
- `numpy`
- `matplotlib`
- `scipy`

Puedes instalarlos con:
```bash
pip install sympy numpy matplotlib scipy
