# MVP Análise de Dados e Boas Práticas

Autor: Thaygor Henrique Gonçalves  
Data: 12/04/2026  

---

## Introdução

A manutenção preditiva tem como objetivo antecipar falhas em equipamentos industriais a partir da análise de dados operacionais, contribuindo para a redução de custos e aumento da eficiência dos processos.

Neste contexto, este projeto aborda um problema de classificação aplicado a um dataset de falhas em máquinas industriais, com o objetivo de identificar padrões e relações entre variáveis operacionais e a ocorrência de falhas.

A análise busca compreender tanto a ocorrência de falhas (falha ou não falha) quanto a distinção entre os diferentes tipos de falha, por meio de técnicas de análise exploratória e preparação dos dados.

---

## Abordagem

Foram aplicadas técnicas de análise exploratória de dados (EDA), incluindo estatísticas descritivas, histogramas, boxplots, matriz de correlação e análise multivariada com pairplot.

As hipóteses foram definidas a partir dos padrões observados e posteriormente validadas com base nas evidências encontradas nos dados, permitindo uma investigação estruturada das relações entre variáveis operacionais e a ocorrência de falhas.

A etapa de pré-processamento contemplou verificação da qualidade dos dados, normalização, padronização e criação de novas variáveis (feature engineering), com foco em melhorar a interpretação e comparabilidade das variáveis.

---

## Notebook do Projeto

[mvp-analise-dados-e-boas-praticas.ipynb](https://github.com/thaygorh/Analise-de-Dados-e-Boas-Praticas/blob/main/mvp-analise-dados-e-boas-praticas.ipynb)

---

## Estrutura do Notebook

O notebook está organizado nas seguintes etapas principais:

1. Definição do Problema  
2. Dataset e Atributos  
3. Hipóteses e Perguntas de Análise  
4. Importação e Carga de Dados  
5. Estrutura dos Dados  
6. Limpeza e Padronização Inicial  
7. Análise Exploratória dos Dados (EDA)  
8. Pré-processamento de Dados (Preparação Final)  
9. Validação das Hipóteses  
10. Conclusão  

---

## Arquivos do Repositório

- [mvp-analise-dados-e-boas-praticas.ipynb](https://github.com/thaygorh/Analise-de-Dados-e-Boas-Praticas/blob/main/mvp-analise-dados-e-boas-praticas.ipynb)  
  Notebook principal contendo toda a análise.

- [Predictive Maintenance Dataset AI4I 2020.csv](https://github.com/thaygorh/Analise-de-Dados-e-Boas-Praticas/blob/main/Predictive%20Maintenance%20Dataset%20AI4I%202020.csv)  
  Dataset utilizado no projeto.

---

## Principais Achados

- A falha por dissipação de calor foi o tipo de falha mais recorrente no dataset.
- Variáveis operacionais como desgaste da ferramenta, torque e velocidade de rotação apresentaram forte relação com a ocorrência de falhas.
- O tipo do produto influenciou tanto a taxa de falha quanto a distribuição dos diferentes modos de falha.
- A variável diferença de temperatura contribuiu para uma interpretação mais clara das condições térmicas associadas às falhas.
