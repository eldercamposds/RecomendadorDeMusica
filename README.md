# Recomendador de Musica
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/eldercamposds/RecomendadorDeMusica/blob/main/LICENSE) 

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

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/devsuperior/sds1-wmazoni

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/devsuperior/sds1-wmazoni

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
yarn install

# executar o projeto
yarn start
```

# Autor

Wellington Mazoni de Andrade

https://www.linkedin.com/in/wmazoni
