# Recomendador de Musica
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/eldercamposds/RecomendadorDeMusica/blob/main/LICENSE) 

Para cessar o projeto completo clique no link abaixo:

[![Static Badge](https://img.shields.io/badge/Clique%20Aqui%20-%20Acesse%20o%20Poejeto%20%2F%20%23fff?style=plastic)](https://colab.research.google.com/github/eldercamposds/RecomendadorDeMusica/blob/main/Recomendador_de_musicas.ipynb)

# Sobre o projeto

Projeto desenvolvido com o objetivo de explorar usualidades da API do Spotify.

A aplicação consiste em um modelo de machine learning desenvolvido em Python, onde serão retornados ao usuário musicas de cantores ou estilos semelhantes ao da busca realizada.

Toda aplicação foi desenvolvida em um ambiente do Google Colab e utilizado analise gráfica para analisar os dados e clusterização para o treinamento da machine learning.

Foi utilizada uma base de dados com cerca de 20311 dados para o treinamento

## Dados
![Dados](https://github.com/eldercamposds/imagens/blob/main/imagem_2023-06-28_212807954.png) 

![Loudness](https://github.com/eldercamposds/imagens/blob/main/imagem_2023-06-28_212843664.png)

![Variações](https://github.com/eldercamposds/imagens/blob/main/imagem_2023-06-28_212857330.png)

![Matriz](https://github.com/eldercamposds/imagens/blob/main/imagem_2023-06-28_212910329.png)

![Disperção](https://github.com/eldercamposds/imagens/blob/main/imagem_2023-06-28_212931101.png)



## Visualizando as recomendações
![Print 1](https://github.com/eldercamposds/imagens/blob/main/imagem_2023-06-28_212947776.png)

![Print 2](https://github.com/eldercamposds/imagens/blob/main/imagem_2023-06-28_213002130.png)


# Projeto desenvolvido em Python com as bibliotecas:
## numnpy
## pandas
## plotly.express
## plotly.graph_objects
## sklearn.pipeline
## sklearn.preprocessing
## sklearn.decomposition
## sklearn.cluster

# Como executar o projeto

## Pré-requisitos
Possuir as chaves client_id e client_secret do Spotify for Developers 
que podem ser solicitadas através deste link: https://developer.spotify.com

```bash

As chaves devem ser inceridas na variavel de mesmo nome localizadas no intem "4.2 Biblioteca Spotipy"

```

