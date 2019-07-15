# Data Wrangling com Python

## Introdução
Uma análise ou predição bem-sucedida depende de dados precisos, bem estruturados e formatados para as diversas finalidades. O Data Wrangling é o processo pelo qual você deve passar para fazer a transição de entradas de fontes de dados brutas em saídas preparadas para serem utilizadas na análise ou em modelos de Machine Learning.

## Objetivo
Este repositório consiste na demonstração das principais técnicas de Tratamento de Dados.

## Data Wrangling consiste em:
- Coleta de Dados
- Formatação
- Estruturação
- Limpeza
- Normalizar
- Padronizar
- Visualização

## Técnicas Utilizados
### Limpeza de Dados Nulos
Em Data Wrangling, uma etapa muito importante para analise e processamento de dados, é a limpeza dos dados nulos, os pontos fluante **NaN** (Not a Number).

#### Métodos de Limpezas de Dados Nulos
Alguns métodos para realizar a limpeza dos dados incompletos:
- Retirada da linha que possui o dado nulo
- Substituição por *dados contidos na colunas*
- Substituição pela *média ou mediana* dos dados contidos
- Substituição pela *frequencia ou por um valor fixo*

### Escalonamento de Dados - Padronização & Normalização
Outra etapa bastante significante, é o processo de padronização e normalização dos dados obtidos. O processo de **normalização** refere-se ao reescalonamento de atributos numéricos de valor real no intervalo 0 e 1. Já a **padronização** refere-se a mudar a distribuição de cada atributo para ter uma média de zero e um desvio padrão de um (variação unitária).

#### Dados não normlizados

<p>
  <img src="https://i.ibb.co/pvC20HK/data.png" width="160">
</p>

<p>
  <img src="https://i.ibb.co/6PV4Twb/plot-data.png" width="550">
</p>

#### Dados normlizados

<p>
  <img src="https://i.ibb.co/23QBDGF/normalizer-data.png" width="180">
</p>

<p>
  <img src="https://i.ibb.co/YQFrdJ0/plot-normalizer.png" width="550">
</p>

### Binning
Também conhecido como **bucketing**, consiste no processo de categorização de dados numéricos.

#### Categorizando 'horsepower'

<p>
  <img src="https://i.ibb.co/y6MNTny/binned1.png" width="210">
</p>

#### Categorizando 'price'

<p>
  <img src="https://i.ibb.co/HtByhXJ/binned2.png" width="160">
</p>

### Variável Dummy
Uma variável dummy é aquela que toma o valor 0 ou 1 para indicar a ausência ou presença de algum efeito categórico.

#### Dummy para Tipo de Combustível
<p>
  <img src="https://i.ibb.co/jLMwD2H/dummy.png" width="110">
</p>

<p>
  <img src="https://i.ibb.co/7V5wQGM/dummy2.png" width="110">
</p>
