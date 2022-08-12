# data-engineering-projects: apache Spark, Airflow, Kafka, data pipeline

Este é um portfólio onde encontra-se uma breve introdução de todos os projetos de engenharia de dados desenvolvidos durante os estudos nesta área. O portfólio é atualizado regularmente na medida que novos projetos forem desenvolvidos.

Caso haja qualquer dúvida, você pode me contactar diretamente através de meu LinkedIn [](https://br.linkedin.com/in/geazi-antunes-aa9264163).

Os projetos foram desenvolvidos principalmente com as seguintes tecnologias:

- Linguagem de programação Python;
- Apache Spark / PySpark: análise e manipulação de dados;
- Pandas: análise de dados;
- Apache Airflow: desenvolvimento e orquestração de pipeline de dados;
- Docker: desenvolvimento por conteinerização;

## BSB: a ETL pipeline using Apache Airflow to extract, transform and load top5 best sellers books from New York Times

O BSB é um projeto que faz o uso de uma pipeline de dados para extrair, transformar e carregar os top5 livros Best Sellers de ficção do New York Times. Toda a orquestração da pipeline é feito com o uso do framework Apache Airflow 2.0, e tanto o datalake quanto o data warehouse faz o uso do banco de dados Não Relacional MongoDB.

Tecnologias utilizadas:

- Apache Airflow: desenvolvimento e orquestração do fluxo de trabalho;
- Web scraping: extração de dados utilizando a biblioteca Requests e BeautifulSoup;
- Banco de dados MongoDB: data lake e data warehouse;
- Docker: desenvolvimento por conteinerização com imagem personalizada;

Para saber mais sobre o desenvolvimento, confira o repositório completo do projeto [aqui](https://github.com/geazi-anc/bsb).

## Dracula: The top most common words in Dracula, by Bram Stoker

Considerado como um marco da literatura gótica, o icônico livro Drácula, escrito em 1897 por Bram Stoker, desperta até hoje o fascínio das pessoas por todo o mundo. A fim de consolidar os conhecimentos iniciais do Apache Spark, desenvolveu-se este notebook para analisar as principais palavras mais comuns encontradas neste clássico livro.

Tecnologias utilizadas:

- Apache Spark / PySpark: análise e manipulação de dados;
- Requests: download automatizado do livro Dracula diretamente do projeto Gutenberg;
- Jupyter: desenvolvimento do notebook;

Para saber mais sobre o desenvolvimento, confira o repositório completo do projeto [aqui](https://github.com/geazi-anc/dracula).

## Pokemonsflow: a data pipeline development with Airflow to extract pokemons via API

Desenvolvimento de uma pipeline de dados para extrair os famosos monstrinhos de bolso, os pokemons, da API PokeAPI. Depois da extração será aplicado algumas transformações bem simples nos dados para que, por fim, possam ser salvos localmente, simulando o carregamento dos dados em um data warehouse.

Tecnologias utilizadas:

- Apache Airflow: desenvolvimento e orquestração da pipeline de dados;
- Requests: extração de dados via API;
- Docker: desenvolvimento por conteinerização;

Este projeto foi desenvolvido para um artigo que escrevi no Medium, que pode ser lido diretamente [aqui](https://medium.com/@geazi.anc/pokemons-flow-desenvolvendo-uma-pipeline-de-dados-com-apache-airflow-para-extra%C3%A7%C3%A3o-de-pokemons-via-4fc982978527).

## Spotify-tracks-analysis: a simple analysis over spotify tracks from winter 2019

Análise exploratória de uma amostra dos dados da biblioteca do Spotify no inverno de 2019.

Tecnologias utilizadas:

- Apache Spark / PySpark: análise e manipulação de dados;
- Pandas: leitura remota do dataset;
- Jupyter: desenvolvimento do notebook;

Para saber mais sobre o desenvolvimento, confira o repositório completo do projeto [aqui](https://github.com/geazi-anc/spotify-tracks-analysis).
