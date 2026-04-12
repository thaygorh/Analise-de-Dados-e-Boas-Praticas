# MVP Análise de Dados e Boas Práticas

Autor: Thaygor Henrique Gonçalves  
Data: 12/04/2026  

---

## Sobre o Projeto

Este projeto tem como objetivo a análise exploratória e o pré-processamento de um dataset de manutenção preditiva, buscando identificar padrões relacionados à ocorrência de falhas em máquinas industriais.

A análise segue as boas práticas de ciência de dados, contemplando desde o entendimento do problema até a preparação dos dados para possíveis aplicações em modelos de machine learning.

Entre os principais resultados obtidos, destacam-se a maior recorrência da falha por dissipação de calor, a relevância de variáveis como torque, velocidade de rotação e desgaste da ferramenta, além da influência do tipo do produto na ocorrência dos diferentes modos de falha.

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

- [mvp-analise-dados-e-boas-praticas.ipynb](https://github.com/thaygorh/Analise-de-Dados-e-Boas-Praticas/blob/main/mvp-analise-dados-e-boas-praticas.ipynb) → Notebook principal contendo toda a análise.

- [Predictive Maintenance Dataset AI4I 2020.csv](https://github.com/thaygorh/Analise-de-Dados-e-Boas-Praticas/blob/main/Predictive%20Maintenance%20Dataset%20AI4I%202020.csv) → Dataset utilizado no projeto.

---

## Principais Achados

- A falha por dissipação de calor foi o tipo de falha mais recorrente no dataset.
- Variáveis como desgaste da ferramenta, torque e velocidade de rotação apresentaram forte relação com a ocorrência de falhas.
- O tipo do produto influenciou tanto a taxa de falha quanto a distribuição dos diferentes modos de falha.
- A criação da variável diferença de temperatura contribuiu para uma interpretação mais clara das condições térmicas associadas às falhas.
