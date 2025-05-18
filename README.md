# FraudDetect

Este projeto tem como objetivo detectar transações fraudulentas em cartões de crédito utilizando o algoritmo **K-Vizinhos Mais Próximos (K-NN)** com base em uma amostragem de um grande dataset de transações reais.

[![Abrir no Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1IdN8LnvkB_m1mFL-OrdKCM3kblCoqPlV?usp=sharing)

## Arquivo principal
- `DataAnalyticsFraudDetect.ipynb`: notebook com todas as etapas de análise, pré-processamento, modelagem e avaliação.

## Sobre o Projeto

Este notebook foi desenvolvido como atividade prática da disciplina de Machine Learning and Modelling na FIAP com base de dados de fraude do [kaggle](https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud/data). O foco principal foi explorar:

- Pré-processamento de dados com `pandas` e `StandardScaler`
- Amostragem de 200.000 registros para otimizar o desempenho
- Treinamento e validação com o algoritmo `KNeighborsClassifier`
- Avaliação com acurácia e matriz de confusão

## Tecnologias utilizadas
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- Google Colab

## Resultado
O modelo apresentou X% de acurácia na detecção de fraudes, com bom equilíbrio entre precisão e recall.

## Autor
Matheus Cardoso Gomes - [LinkedIn](www.linkedin.com/in/matheus-cardoso-70552b138)
