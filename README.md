# 📈 Stochastic Signal Analysis & Time Series Modeling

<div align="center">

![Python](https://img.shields.io/badge/python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Statistics](https://img.shields.io/badge/Stat-Bayesian_Inference-orange?style=for-the-badge)
![Math](https://img.shields.io/badge/Math-Stochastic_Processes-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Research-lightgrey?style=for-the-badge)

</div>

> **Explorando a matemática por trás da modelagem de dados ruidosos, inferência probabilística e decomposição de sinais.**

Este repositório reúne implementações focadas nos fundamentos estatísticos necessários para **Análise Quantitativa** e **Processamento de Sinais**. O objetivo não é apenas aplicar bibliotecas, mas investigar o comportamento matemático de modelos em cenários de incerteza.

---

## 🔬 Módulos de Estudo

### 1. Bayesian Hypothesis Selection
* **O Conceito:** Aplicação do Teorema de Bayes para selecionar a melhor hipótese dado um conjunto de dados ruidosos ($d$).
* **Aplicação em Finanças:** Fundamental para **Regime Switching** (detectar se o mercado mudou de tendência) e atualização de probabilidades em tempo real.
* **Técnica:** Cálculo da probabilidade *a posteriori* $P(h|d)$ baseada na verossimilhança.

### 2. Stochastic Signal Analysis
* **O Conceito:** Análise de sinais aleatórios, focando em propriedades estatísticas como média, variância e autocorrelação.
* **Aplicação em Finanças:** Modelagem de preços de ativos (Random Walks), análise de volatilidade e filtragem de ruído em séries temporais financeiras.

### 3. Polynomial Regression & Overfitting
* **O Conceito:** Estudo do impacto da complexidade do modelo (grau do polinômio) no erro de generalização.
* **Aplicação em Finanças:** Entendimento visual do **Bias-Variance Tradeoff**. Mostra os perigos de "curve fitting" em backtests (ajustar demais o modelo aos dados passados).

---

## 📊 Visualizações Chave

*(Espaço reservado: Adicione aqui 1 gráfico do notebook de Bayes mostrando as probabilidades mudando e 1 gráfico do notebook de Polinômios mostrando o ajuste da curva)*

---

## 🛠️ Tech Stack
* **Core:** `NumPy`, `SciPy`
* **Visualization:** `Matplotlib`
* **Methodology:** Inferência Estatística, Cálculo Numérico.

## 🚀 Como Rodar
```bash
git clone [https://github.com/cockles98/stochastic-signal-analysis.git](https://github.com/cockles98/stochastic-signal-analysis.git)
cd stochastic-signal-analysis
pip install numpy matplotlib scipy jupyter
jupyter notebook
```

-----

\<div align="center"\>

\<p\>
Estudos desenvolvidos focando em modelagem matemática rigorosa.
\</p\>

\</div\>
