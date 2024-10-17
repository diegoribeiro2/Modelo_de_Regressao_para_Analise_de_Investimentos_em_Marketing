# Estudo de Caso: Construção de um Modelo de Regressão para Análise de Investimentos em Marketing

## Introdução

Neste projeto, eu desenvolvi um modelo de regressão com o objetivo de analisar o desempenho de investimentos em publicidade online realizados por uma empresa. A empresa investe mensalmente em plataformas como YouTube, Facebook e jornais para prospecção de leads (pessoas interessadas em seus produtos). Para monitorar o desempenho desses investimentos, ela registra todos os gastos com publicidade e os retornos de vendas gerados.

A partir desses dados, busquei entender melhor a relação entre as variáveis presentes nos registros e identificar os fatores que mais impactam na geração de leads. Além disso, o objetivo foi criar um modelo preditivo capaz de estimar o retorno de vendas com base em um determinado investimento em publicidade.

## Dados Utilizados

O conjunto de dados contém informações sobre os investimentos feitos nas plataformas de publicidade e os valores das vendas geradas. As colunas do dataset incluem:

- **youtube**: Investimento realizado na plataforma YouTube
- **facebook**: Investimento realizado na plataforma Facebook
- **newspaper**: Investimento realizado em jornais
- **sales**: Valor das vendas geradas

## Análise Descritiva

Comecei importando o dataset e utilizando a biblioteca Pandas para explorar e manipular os dados. Identifiquei inconsistências, como valores ausentes, dados duplicados e outliers. A análise descritiva das variáveis revelou informações valiosas sobre a distribuição dos dados e a natureza de cada variável.

## Análise Exploratória

Na fase de análise exploratória, utilizei gráficos e visualizações para identificar padrões, relações e tendências entre as variáveis. As correlações entre os investimentos em publicidade e as vendas foram examinadas, permitindo-me entender como cada plataforma impacta no retorno.

## Modelagem

Para construir o modelo de regressão, utilizei as bibliotecas necessárias e implementei um modelo de regressão linear simples. A partir disso, treinei o modelo com os dados disponíveis e realizei ajustes conforme necessário. O foco foi garantir que o modelo pudesse prever o retorno de vendas com base nos diferentes níveis de investimento.

## Predição

Por fim, apliquei o modelo de regressão para realizar previsões de retorno de vendas geradas a partir dos investimentos em publicidade. Essas previsões forneceram insights sobre o impacto dos diferentes níveis de investimento em marketing nas vendas, auxiliando na tomada de decisões estratégicas para a empresa.
