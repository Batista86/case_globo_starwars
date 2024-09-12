
# Case para Análise de Dados Star Wars

Este projeto visa realizar análises de dados sobre o universo Star Wars utilizando o banco de dados DuckDB. Os dados são extraídos de arquivos JSON e organizados em tabelas para facilitar a análise de informações sobre personagens, planetas, naves espaciais e filmes.


## Estrutura do Projeto


O projeto é composto pelos seguintes arquivos e diretórios:

starwars.db: Arquivo do banco de dados DuckDB onde os dados estão armazenados.
personagens.json: Arquivo JSON contendo dados sobre personagens de Star Wars.
planets.json: Arquivo JSON contendo dados sobre planetas.
starships.json: Arquivo JSON com informações sobre naves espaciais.
films.json: Arquivo JSON com dados sobre os filmes de Star Wars.
notebooks/case.ipynb: Notebook com o código para a criação do banco de dados e análises realizadas.


## Tabelas Criadas

As seguintes tabelas foram criadas no DuckDB a partir dos arquivos JSON:

personagens: Tabela que armazena informações sobre os personagens de Star Wars, incluindo nome, altura, peso, gênero e outras características relevantes.

planets: Tabela que armazena dados sobre os planetas, como nome, clima, terreno e população.

starships: Tabela que armazena dados sobre as naves espaciais, incluindo nome, modelo, fabricante e capacidade de carga.

films: Tabela que lista os filmes de Star Wars, incluindo título, data de lançamento, diretor e outras informações relevantes.


## Referência

 - [What happened to Swapi](https://swapi.dev/)
 - [Swapi Documentation](https://swapi.dev/documentation)

