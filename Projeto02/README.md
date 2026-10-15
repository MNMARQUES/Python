# Projeto de Análise de Dados com Python — Módulo 2

## 1. Objetivo do projeto

O objetivo deste projeto foi aplicar os conceitos fundamentais de análise de dados utilizando Python e bibliotecas especializadas em manipulação, tratamento, análise estatística e visualização de dados.

A atividade consistiu na criação e análise de dois conjuntos de dados fictícios de clientes: um relacionado às características físicas e outro contendo informações demográficas e socioeconômicas. A partir desses dados, foi desenvolvido um fluxo de análise para identificar distribuições, padrões e possíveis relações entre as variáveis.

## 2. Ferramentas e tecnologias utilizadas

- **Python:** linguagem de programação utilizada para desenvolver e executar as etapas da análise.
- **Google Colab:** ambiente de desenvolvimento em nuvem utilizado para escrever e executar o código Python.
- **Pandas:** biblioteca utilizada para leitura de arquivos CSV, manipulação de tabelas, tratamento de dados ausentes, remoção de duplicados e análise estatística.
- **NumPy:** utilizada na geração e manipulação de dados numéricos, com foco na reprodutibilidade dos experimentos.
- **Matplotlib:** utilizada na construção e personalização de gráficos.
- **Seaborn:** utilizada na criação de visualizações estatísticas para facilitar a identificação de padrões nos dados.

## 3. Etapas desenvolvidas

O projeto foi dividido em etapas para organizar o processo de análise:

1. **Geração e coleta de dados:** criação de dois arquivos CSV fictícios, representando características físicas e informações demográficas dos clientes.
2. **Análise exploratória:** inspeção das dimensões dos conjuntos de dados, tipos de variáveis, estatísticas descritivas, valores ausentes e registros duplicados.
3. **Tratamento e limpeza:** eliminação de registros com valores ausentes por meio do método `dropna()` e remoção de linhas integralmente duplicadas com `drop_duplicates()`.
4. **Integração dos dados:** utilização do método `merge()` para relacionar os conjuntos por meio do identificador único do cliente.
5. **Análise estatística:** cálculo de médias, medianas, frequências, agrupamentos por categorias e correlações entre variáveis numéricas.
6. **Visualização dos resultados:** criação de gráficos para analisar a distribuição de idades, a quantidade de clientes por cidade, a distribuição de renda por escolaridade e a correlação entre variáveis.
7. **Documentação:** geração de relatórios e arquivos de resultados para registrar as etapas realizadas e facilitar a interpretação dos dados.

## 4. Resultados e aprendizados

A execução do projeto permitiu praticar um fluxo completo de análise de dados, desde a preparação da base até a apresentação visual dos resultados.

A atividade demonstrou a importância da qualidade dos dados para a obtenção de análises consistentes, além da utilidade das bibliotecas Python para automatizar tarefas de limpeza, organização, cálculo estatístico e geração de gráficos.

Também foi possível compreender como a integração de diferentes fontes de informação amplia as possibilidades de análise e como as visualizações ajudam a comunicar resultados de maneira mais clara.

## 5. Conclusão

O projeto consolidou conhecimentos fundamentais de Python aplicado à análise de dados, com ênfase na utilização de Pandas, NumPy, Matplotlib e Seaborn. As etapas desenvolvidas reforçaram a importância da análise exploratória, do tratamento adequado dos dados e da interpretação criteriosa dos resultados.

**Observação:** como os arquivos originais do desafio não estavam disponíveis, foram utilizados dados sintéticos criados para fins didáticos. Portanto, os resultados obtidos demonstram a aplicação das técnicas estudadas, mas não correspondem necessariamente aos resultados do conjunto de dados original fornecido pelo professor.
