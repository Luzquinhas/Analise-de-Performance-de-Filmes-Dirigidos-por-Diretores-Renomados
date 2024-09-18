# Analise-de-Performance-de-Filmes-Dirigidos-por-Diretores-Renomados

## Descrição

Este projeto visa analisar a performance de filmes dirigidos por diretores renomados usando um conjunto de dados do Rotten Tomatoes. A análise inclui a exploração de diversas questões de pesquisa avançadas sobre críticas, bilheteira, popularidade, e outros aspectos da performance de filmes.

## Dataset

O arquivo utilizado para esta análise é o `rotten_tomatoes_movies`. Você pode acessar o dataset [aqui](https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset/data).

### Colunas Relevantes
- `movie_title`: Título do filme
- `directors`: Diretores do filme
- `genres`: Gêneros do filme
- `original_release_date`: Data de lançamento original
- `tomatometer_rating`: Avaliação da crítica (Rotten Tomatoes)
- `audience_rating`: Avaliação do público
- `tomatometer_count`: Número de avaliações da crítica
- `audience_count`: Número de avaliações do público
- `runtime`: Duração do filme
- `production_company`: Empresa de produção

## Dependências

Certifique-se de que você tem as seguintes bibliotecas instaladas:


```
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression
import numpy as np
from scipy.stats import ttest_ind
```
## 1. Exploração e Limpeza dos Dados
Carregar o arquivo CSV e identificar as principais colunas.
Limpar e organizar os dados, removendo valores faltantes ou inválidos.
## 2. Definir Diretores Renomados
Criar uma lista de diretores renomados com base em métricas como número de filmes e premiações.

##3. Perguntas de Pesquisa
