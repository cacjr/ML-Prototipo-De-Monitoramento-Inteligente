# SafeForge — Industrial Risk Prediction

## Sobre o Projeto

A SafeForge é uma metalúrgica do interior de São Paulo especializada na produção de peças automotivas. Após incidentes envolvendo altas temperaturas e proximidade de operadores com prensas industriais, a empresa decidiu investir em um sistema inteligente de monitoramento de risco operacional.

Este projeto foi desenvolvido na disciplina **Machine Learning & Modelling**, utilizando o dataset `safeforge_industrial_risk_advanced.csv` para construir modelos capazes de classificar situações como:

* `safe`
* `unsafe`

O objetivo é prever riscos operacionais por meio de técnicas de Machine Learning supervisionado, substituindo regras fixas por modelos capazes de aprender padrões complexos presentes nos dados.

---

## Objetivos

* Realizar análise exploratória dos dados (EDA)
* Aplicar técnicas de limpeza e pré-processamento
* Treinar e comparar modelos de classificação
* Avaliar desempenho utilizando métricas de classificação
* Interpretar os resultados no contexto industrial da SafeForge

---

## Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* LightGBM
* CatBoost

---

## Etapas do Projeto

### 1. Análise Exploratória dos Dados

* Estatísticas descritivas
* Distribuição da variável alvo
* Correlações
* Identificação de outliers
* Análise de variáveis categóricas e numéricas

### 2. Pré-processamento

* Tratamento de valores ausentes
* Holdout treino/teste
* Normalização de variáveis numéricas
* One Hot Encoding

### 3. Modelagem

Modelos treinados:

* Regressão Logística
* Decision Tree
* Random Forest
* XGBoost
* LightGBM
* CatBoost

### 4. Avaliação

Métricas utilizadas:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC AUC

### 5. Interpretação

* Comparação entre modelos
* Importância das variáveis
* Análise dos resultados para prevenção de riscos industriais

---

## Estrutura do Projeto

```bash
├── data/
│   └── safeforge_industrial_risk_advanced.csv
│
├── notebooks/
│   └── Checkpoint5_ML_SafeForge_Refatorado.ipynb
│
├── README.md
└── requirements.txt
```

---

## Resultado

Os modelos ensemble apresentaram melhor desempenho na classificação de risco operacional, demonstrando maior capacidade de capturar relações complexas entre fatores ambientais, humanos e operacionais.

O projeto contribui para a construção de sistemas industriais mais seguros, permitindo ações preventivas antes da ocorrência de acidentes.
