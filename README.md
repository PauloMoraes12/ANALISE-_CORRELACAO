# Análise de Correlação e Associação em Dados de Vendas

Este projeto apresenta uma análise estatística aplicada com foco na
**correlação e associação entre variáveis quantitativas e categóricas**
em um conjunto de dados de vendas.

O objetivo principal é demonstrar **a escolha correta de métodos
estatísticos**, evitando o uso inadequado de coeficientes de correlação
tradicionais em variáveis categóricas, além de comunicar resultados de
forma clara e estruturada.

---

## Objetivo do Projeto

- Aplicar correlação de **Pearson** e **Spearman** em variáveis quantitativas
- Avaliar associação entre variáveis categóricas com **Qui-quadrado** e **Cramér’s V**
- Comparar médias entre grupos utilizando **ANOVA**
- Demonstrar boas práticas de análise exploratória e estatística aplicada
- Construir um projeto organizado para portfólio no GitHub

---

## Variáveis Analisadas

| Variável | Tipo Estatístico |
|--------|----------------|
| `quantidade` | Quantitativa discreta |
| `preco_unitario` | Quantitativa contínua |
| `valor_total` | Quantitativa contínua |
| `tipo_produto` | Categórica nominal |
| `forma_pagamento` | Categórica nominal |

---

## Metodologias Utilizadas

- Correlação de **Pearson**
- Correlação de **Spearman**
- Teste **Qui-quadrado**
- **Cramér’s V** para força da associação
- **ANOVA** para comparação de médias entre grupos
- Visualizações com gráficos de dispersão e boxplots

---

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy

---

## Estrutura do Repositório

```text
analise-correlacao-vendas/
│
├── data/
│   └── vendas.csv
│
├── notebooks/
│   └── 01_analise_correlacao_github.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
