# ex1
Exercício Prático 1

1. Configure o ambiente com as bibliotecas necessárias (pandas, statsmodels, scipy, matplotlib, ect.) 
2. Use um gestor de ambientes ou mantenha um arquivo requirements.txt

Resolva os exercícios abaixo:

## 1. Gráficos

a. Use o gafa dataset. Analise o preço de ações do Google em 2018. É white noise?<br>
b. Use o dataset `aus_retail`. Crie o plot temporal, subseries, lag e ACF. Você consegue observar alguma sazonalidade, ciclo ou tendência?

## 2. Transformações e Decomposição de Séries Temporais
a. Considere a informação do GDP no `global_economy`. Plot o GDP per capita para cada país ao longo do tempo. Qual país tem o maior GDP per capita? Como isto tem mudado ao longo do tempo?<br>
b. Qual transformação Box-Cox você selecionaria para aplicar ao exercício **b** do item **Gráficos**?<br>
c. Para as seguintes séries encontre a transformação Box-Cox adequada, com o objetivo de estabilizar a variância.<br>
  - Tobacco de `aus_production`
  - Economy class passengers de Melbourne para Sydney para o dataset `ansett`.

d. Considere os últimos 5 anos de produção de Gasolina do dataset `aus_production`.
- Faça o plot da série temporal. Você consegue identificar padrões de sazonalidade, tendência, ciclo?
- Faça a decomposição STL. É preciso aplicar alguma transformação para obter uma decomposição adequada?

