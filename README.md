# 📁 Análise de Dados e Modelos de Machine Learning - Insper

Este repositório contém a atividade desenvolvida no primeiro trimestre do **Programa Avançado em Data Science e Decisão** do **Insper**, com foco em análise exploratória de dados e aplicação de modelos preditivos utilizando **R**.

## 📌 Contexto

O objetivo do trabalho foi analisar um conjunto de dados do mercado imobiliário da cidade de São Paulo, disponível publicamente no Kaggle, e construir modelos de regressão para prever o valor de aluguel dos imóveis. O trabalho teve como foco a aplicação prática de conceitos fundamentais de análise de dados, visualização e machine learning.

> **Nota final do trabalho: 10**  
> Trabalho em grupo — 1º trimestre do curso

## 🧠 Desafios propostos

A atividade envolveu as seguintes etapas:

1. **Análise exploratória dos dados**

   - Cálculo da frequência absoluta e relativa da variável `Negotiation.Type`
   - Identificação dos 10 distritos com maior número de imóveis
   - Gráficos de dispersão entre preço do condomínio e preço anunciado, com segmentações por tipo de negociação

2. **Preparação dos dados para modelagem**

   - Filtragem para considerar apenas imóveis para aluguel
   - Divisão dos dados em conjuntos de treino e teste

3. **Modelagem preditiva**  
   Avaliação dos seguintes modelos para previsão do valor de aluguel:

   - Regressão Linear
   - Regressão Ridge
   - Regressão LASSO
   - Árvore de Decisão
   - Floresta Aleatória

   As variáveis preditoras foram selecionadas com base em análise exploratória e conhecimento do domínio.

4. **Avaliação de desempenho**
   - Utilização da métrica RMSE (Root Mean Squared Error) para comparação entre os modelos

## 🛠️ Tecnologias utilizadas

- Linguagem: **R**
- Pacotes principais: `tidyverse`, `ggplot2`, `caret`, `glmnet`, `rpart`, `randomForest`
- Fonte dos dados: [Kaggle – São Paulo Real Estate - Sale/Rent - April 2019](https://www.kaggle.com/datasets/argonalyst/sao-paulo-real-estate-sale-rent-april-2019)

## 📁 Estrutura dos arquivos

```
├── analise_dados_01.Rmd   # Código-fonte em R Markdown com toda a análise
├── analise_dados_01.html            # Versão final do trabalho em HTML
├── sao-paulo-properties-april-2019.csv # Arquivo com a base de dados utilizada
└── README.md                        # Este arquivo
```

## 📚 Aprendizados

Este trabalho foi essencial para consolidar conceitos de:

- Manipulação e limpeza de dados com R
- Visualização de dados para insights exploratórios
- Seleção e avaliação de modelos de regressão
- Uso prático de técnicas supervisionadas para problemas reais
