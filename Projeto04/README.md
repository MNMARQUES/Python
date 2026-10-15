# Projeto Python Avançado — Redes Neurais Artificiais para Regressão

## Objetivo do projeto

O objetivo deste projeto foi aplicar conceitos avançados de Python e aprendizado de máquina para desenvolver modelos de redes neurais artificiais do tipo MLP (Multilayer Perceptron), destinados à previsão do valor médio de imóveis utilizando a base de dados Boston Housing.

O trabalho buscou demonstrar como diferentes arquiteturas de redes neurais podem aprender relações entre variáveis socioeconômicas e características dos bairros, permitindo estimar valores imobiliários a partir dos dados disponíveis.

## Ferramentas e tecnologias utilizadas

- **Python:** linguagem utilizada para implementar o projeto.
- **Google Colab:** ambiente de desenvolvimento e execução dos experimentos.
- **Pandas e NumPy:** manipulação dos dados e cálculos numéricos.
- **Scikit-learn:** carregamento da base, separação dos dados, padronização, treinamento e avaliação dos modelos.
- **Matplotlib:** criação de gráficos para análise dos resultados.
- **MLPRegressor:** implementação da rede neural artificial para regressão.

## Metodologia

Inicialmente, a base de dados foi importada e suas variáveis foram separadas em entradas e saída. A variável MEDV foi definida como alvo da previsão, enquanto as demais características foram utilizadas como variáveis explicativas.

Em seguida, os dados foram divididos em conjuntos de treinamento e teste, utilizando a função `train_test_split`. A padronização das variáveis de entrada foi realizada por meio de `StandardScaler`, integrado ao pipeline de cada modelo para evitar vazamento de informações do conjunto de teste.

Foram treinadas quatro arquiteturas de redes neurais MLP: três com uma camada oculta de 16, 32 e 64 neurônios, respectivamente, e uma quarta arquitetura com duas camadas ocultas, contendo 32 e 16 neurônios.

Os modelos foram comparados por meio das métricas MAE, MSE, RMSE e R². Também foram produzidos gráficos para facilitar a interpretação dos erros e a comparação entre valores reais e previstos.

## Resultados e conclusão

A comparação dos modelos permitiu avaliar como a quantidade de neurônios e a profundidade da rede influenciam o desempenho preditivo. O modelo com menor RMSE foi identificado como o de melhor resultado segundo esse critério, considerando os dados de teste.

O projeto consolidou conhecimentos sobre preparação de dados, regressão supervisionada, redes neurais artificiais, ajuste de hiperparâmetros e avaliação de modelos de aprendizado de máquina.

Conclui-se que a experimentação com diferentes arquiteturas é importante para identificar configurações mais adequadas a um problema. O melhor desempenho deve ser determinado pelos resultados efetivamente obtidos, e não apenas pela complexidade da rede neural.

**Observação:** a base Boston Housing possui limitações históricas e variáveis relacionadas a questões sociais sensíveis. Seus resultados devem ser interpretados como um exercício acadêmico, não como recomendação para avaliação imobiliária real ou tomada de decisões sobre pessoas e comunidades.
