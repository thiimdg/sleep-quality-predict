# Projeto de Análise e Predição da Qualidade de Sono

Este projeto tem como objetivo desenvolver uma análise exploratória de dados relacionados a qualidade do sono e no fim desenvolver um algoritmo de machine learning para realizar previsões.

## Sobre o Projeto

Objetivo: Criar um modelo preditivo que estime a qualidade do sono de um indivíduo a partir de dados observados.

Modelos utilizados: Regressão Linear e Random Forest.

Resultados: O Random Forest apresentou melhor desempenho, com R² = 0.98 e MAE = 0.11.

## Como Usar

1) Instale os Requerimentos

```bash
pip install -r requirements.txt
```

Para abrir o notbook diretamente no Google Colab clique no botão "Open in Colab".

Faça o upload do dataset quando solicitado.

## Estrutura do Projeto

```
├── Health_Sleep_Statistics.csv  # Dataset utilizado
├── HealthSleepStatistics.ipynb  # Notbook
├── README.md              # Este arquivo
└── requirements.txt       # Dependências
```

## Principais Resultados

Modelo	- R² Score	- MAE	= RMSE

Regressão Linear	- 0.96	- 0.25	- 0.35

Random Forest -	0.98	- 0.11	- 0.26

## Próximos Passos

Feature Engineering: Criar novas variáveis para utilização.

Testar outros modelos, como XGBoost por exemplo.
