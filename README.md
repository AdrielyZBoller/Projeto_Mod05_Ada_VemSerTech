# Projeto_Mod05_Ada_VemSerTech
Repositório para o desenvolvimento do projeto 5 - Estatística I. 

Equipe:
- [Adriely](https://www.linkedin.com/in/adrielyzambiasiboller/)
- [Amanda](https://www.linkedin.com/in/amanda-rs/)

Professor:
- [Rogério Mainardes](https://www.linkedin.com/in/rogerioomds/)

# Visão Geral do Projeto
✈️Este repositório contém um conjunto de scripts em Python para realizar análises de dados do [Airlines Delay](https://www.kaggle.com/datasets/giovamata/airlinedelaycauses).

🔍 Os dados trabalhados são obtidos pela Bureau of Transportation Statistics (BTS) do Departamento de Transportes dos EUA (DOT), que monitora o desempenho pontual de voos domésticos operados por grandes transportadoras aéreas. O DataFrame fornece informações resumidas sobre o número de voos pontuais, atrasados, cancelados e desviados. Esses dados são compilados a partir da Statistical Computing Statistical Graphics 2009 Data Expo.

Para o desenvolvimento do projeto utilizou os seguintes pacotes Python:
- ``pandas``
- ``numpy``
- ``matplotlib``
- ``Seaborn``

Objetivos:
- Realizar uma análise descritiva por completo da base (Variáveis discretas e contínuas);
- Avaliar a distribuição de probabilidade de variáveis contínuas que considera mais interessante;

## Análises Realizadas

Inicialmente foram removidas algumas colunas consideradas desnecessárias. E posteriomente feita uma análise exploratória dos dados.
Com as análises observou-se que o dataframe original apresenta muitos outliers. E para evitar a perda de informações significativas, foi relevante separar em:
- [Voos Atrasados](https://github.com/AdrielyZBoller/Projeto_Mod05_Ada_VemSerTech/blob/main/analise_atrasados.ipynb)
- [Voos Cancelados](https://github.com/AdrielyZBoller/Projeto_Mod05_Ada_VemSerTech/blob/main/analise_cancelados.ipynb)
- [Voos Sem Atraso Justificado](https://github.com/AdrielyZBoller/Projeto_Mod05_Ada_VemSerTech/blob/main/analise_sem_atraso_justificados.ipynb)
- [Voos Adiantados](https://github.com/AdrielyZBoller/Projeto_Mod05_Ada_VemSerTech/blob/main/analise_adiantados.ipynb)
- [Voos Desviados](https://github.com/AdrielyZBoller/Projeto_Mod05_Ada_VemSerTech/blob/main/analise_desviados.ipynb)

## Dicionário de Variavéis
- [Dicionário](https://github.com/AdrielyZBoller/Projeto_Mod05_Ada_VemSerTech/blob/main/dicionario.ipynb)