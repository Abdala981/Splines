[![Open In Colab](https://colab.research.google.com/drive/1TO2-KxVZ6U2mkbEppP3TZfnNklzFXOSJ?authuser=1#scrollTo=Snpw3yGrRTwm)]

# Natural Cubic Spline Interpolation 📈

Implementação em Python do algoritmo de **Interpolação por Spline Cúbica Natural**.

O objetivo deste projeto é demonstrar a construção matemática da curva suave que conecta um conjunto de pontos, resolvendo manualmente o sistema linear tridiagonal, sem depender de funções "caixa preta" como `scipy.interpolate`.

## 🚀 Funcionalidades

- **Algoritmo Manual:** Implementação passo a passo do cálculo dos coeficientes (a, b, c, d).
- **Visualização:** Plotagem dos dados originais vs. curva interpolada usando `matplotlib`.
- **Eficiência:** Geração vetorizada dos pontos para plotagem.

## 🛠️ Tecnologias

- Python 3.x
- NumPy (Álgebra linear e vetores)
- Matplotlib (Visualização)

## 📦 Como rodar

1. Clone o repositório:
   ```bash
    git clone [https://github.com/Abdala981/Splines.git](https://github.com/Abdala981/Splines.git)
Instale as dependências:

  ```bash
    pip install numpy matplotlib
```

Execute o script:

  ```bash

    python spline_cubica.py
