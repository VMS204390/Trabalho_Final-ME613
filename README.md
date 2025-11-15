Projeto de Regressão Linear – Previsão de Aluguel de Bicicletas

Este projeto tem como objetivo desenvolver e avaliar um modelo de regressão linear para prever o número total de bicicletas alugadas (cnt) com base em variáveis ambientais, temporais e comportamentais associadas ao uso do serviço de aluguel.

## Descrição do Banco de Dados

O conjunto de dados utilizado contém informações diárias sobre o aluguel de bicicletas, acompanhadas de variáveis explicativas que podem influenciar a demanda. As variáveis disponíveis são:

dteday – Data do registro de aluguel

season – Estação do ano

1: Primavera

2: Verão

3: Outono

4: Inverno

yr – Ano

0: 2018

1: 2019

month – Mês do ano (1 a 12)

holiday – Indica se o dia é feriado (0: não, 1: sim)

weekday – Dia da semana

1: Domingo

2: Segunda-feira

…

7: Sábado

workingday – Indica se é dia útil (0: não, 1: sim)

weather – Situação climática

1: Céu limpo

2: Neblina/Nublado

3: Neve/chuva leve

4: Chuva forte/neve

temp – Temperatura em graus Celsius

atemp – Sensação térmica em graus Celsius

hum – Umidade relativa (%)

windspeed – Velocidade do vento

casual – Número de usuários casuais

registered – Número de usuários registrados

cnt – Número total de bicicletas alugadas (casual + registered)

## Objetivo do Projeto

O foco principal é construir um modelo preditivo capaz de estimar o total de bicicletas alugadas em um determinado dia, utilizando as variáveis disponíveis no dataset. Por meio da regressão linear, buscamos:

Identificar quais variáveis mais influenciam o volume de aluguel;

Avaliar a relação entre fatores climáticos, calendário e comportamento dos usuários;

Produzir um modelo simples, interpretável e estatisticamente consistente.

## Etapas Desenvolvidas

Análise exploratória dos dados (EDA)

Tratamento e preparação das variáveis

Construção do modelo de regressão linear

Avaliação do desempenho do modelo

Interpretação dos coeficientes e discussão dos resultados

📌 Resultados Esperados

Este projeto pretende demonstrar, de maneira clara e prática, como técnicas de regressão linear podem ser utilizadas para problemas reais de previsão de demanda, auxiliando na gestão de sistemas de mobilidade urbana e na otimização de recursos.
