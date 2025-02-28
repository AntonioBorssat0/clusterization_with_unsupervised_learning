# Clusterization of Movies Synopsis

Este projeto tem por finalidade praticar os conceitos discutidos na disciplina de Ciência de Dados do curso de Mestrado em Informática da UFES, principalmente: representação e pré-processamento de textos, aprendizado não supervisionado para clusterização e visualização de dados.

## Conjunto de Dados

Para este projeto, utilizamos um conjunto de dados de filmes obtido de várias fontes, incluindo IMDb. Os dados estão organizados em um arquivo `.csv` com as seguintes colunas:

- **genres** - gêneros a que um filme pertence. Um filme pode estar associado a mais de um gênero.
- **sinopse** - sinopse do filme.
- **startYear** - ano de lançamento do filme.
- **primaryTitle** - título do filme.
- **runtimeMinutes** - duração do filme, em minutos.
- **averageRating** - média das avaliações do filme.
- **numVotes** - número de avaliações do filme.
- **actors_names** - principais atores/atrizes do filme.
- **directors_names** - diretores(as) do filme.

**Observação:** este conjunto de dados é uma versão transformada dos dados originais. Por exemplo, gêneros muito populares ou raros foram removidos.

## Objetivo

Utilizar aprendizado não supervisionado (neste caso, agrupamento) para investigar se há relação entre a sinopse de um filme e o(s) gênero(s) a que pertence. Especificamente, vamos agrupar os filmes de acordo com suas sinopses e verificar a distribuição dos gêneros em cada grupo. Ou seja, se os filmes pertencentes ao mesmo grupo compartilham gêneros semelhantes.

## Execução

Para executar o projeto, abra o arquivo `Clusterization of movies synopsis.ipynb` em um ambiente Jupyter Notebook ou Google Colab e execute as células em ordem.

## Estrutura do Projeto

- **Descrição:** Introdução e objetivo do projeto.
- **Conjunto de Dados:** Detalhes sobre o conjunto de dados utilizado.
- **Objetivo:** Explicação do objetivo do projeto.
- **Início do Trabalho:** Instalação de pacotes necessários e carregamento dos dados.
- **Análise de Dados:** Verificação e limpeza dos dados.
- **Agrupamento:** Aplicação de técnicas de aprendizado não supervisionado (KMeans) para agrupamento das sinopses dos filmes.
- **Visualização:** Visualização dos resultados dos agrupamentos e análise da distribuição dos gêneros.
