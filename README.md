# Detecção de Fraude em Cartões de Crédito

Este projeto realiza uma análise de dados para detecção de fraudes em transações com cartões de crédito. Utilizando diferentes modelos de machine learning, o objetivo é identificar transações fraudulentas com precisão, avaliando o desempenho de modelos como Regressão Logística, Árvores de Decisão e Random Forest.

## Autor
Gabriel Menegueli

## Base de Dados

Os dados utilizados neste projeto foram obtidos a partir do [Kaggle - Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data). Este dataset contém transações realizadas por cartões de crédito em setembro de 2013 por titulares de cartões europeus. Ele apresenta um desbalanceamento significativo, com uma minoria de transações sendo fraudulentas.

## Descrição

O notebook neste projeto foi desenvolvido para ensinar e demonstrar como diferentes técnicas de machine learning podem ser aplicadas para a detecção de fraudes. Ele é bem comentado e organizado em etapas para facilitar o entendimento, especialmente para iniciantes na área de ciência de dados.

## Estrutura do Projeto

- **Etapa 1: Carregando e Visualizando os Dados**: Nesta etapa, os dados são carregados e visualizados, e são fornecidas informações básicas sobre o dataset.
  
- **Etapa 2: Análise Exploratória de Dados (EDA)**: Aqui, uma análise exploratória é realizada para entender melhor as características dos dados, como a distribuição das classes e as correlações entre as variáveis.

- **Etapa 3: Preparação dos Dados**: Os dados são preparados para a modelagem, incluindo a normalização de variáveis e a divisão dos dados em conjuntos de treino e teste.

- **Etapa 4: Treinamento do Modelo com Regressão Logística**: Um modelo de Regressão Logística é treinado e avaliado nesta etapa.

- **Etapa 5: Treinamento com Árvores de Decisão**: Nesta etapa, um modelo de Árvore de Decisão é treinado e comparado com os resultados da Regressão Logística.

- **Etapa 6: Treinamento com Random Forest**: Um modelo de Random Forest é treinado e sua performance é comparada com os modelos anteriores.

- **Conclusão e Próximos Passos**: A seção final discute os resultados dos modelos e sugere próximos passos para aprimorar a detecção de fraudes.

## Como Entender os Gráficos

- **Relatório de Classificação**: Mostra métricas importantes como precisão, recall, e F1-score para cada classe.
  
- **Matriz de Confusão**: Indica quantas previsões o modelo fez corretamente e quantas ele errou. Neste caso, as classes `0` e `1` representam transações não fraudulentas e fraudulentas, respectivamente.

- **Distribuição das Classes**: Mostra a quantidade de transações fraudulentas e não fraudulentas, evidenciando o desbalanceamento dos dados.

## Próximos Passos

1. Continuar experimentando com outros modelos de machine learning.
2. Implementar técnicas de balanceamento de classes, como SMOTE.
3. Considerar a implementação de um sistema de detecção de fraudes em tempo real, com monitoramento contínuo e reentrenamento do modelo.
