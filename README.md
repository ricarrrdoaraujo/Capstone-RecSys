# Capstone Project | Machine Learning Engineer
## Modelo de um Sistema de Recomendação de Filmes

### Instalação
Este projeto requer **Python 3.x** e as seguintes bibliotecas instaladas:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [Surprise](http://surprise.readthedocs.io/en/stable/index.html)
- [Wordcloud](https://amueller.github.io/word_cloud/)

Você também precisará ter software instalado para rodar e executar um [Jupyter Notebook](http://ipython.org/notebook.html)

Se você ainda não tem o Python instalado, é altamente recomendado que instale a distribuição [Anaconda](http://continuum.io/downloads), que já tem os pacotes acima incluídos. Certifique-se de selecionar o instalador 3.x.

### Código

Todo código do projeto foi implementado dentro do iPython notebook que se encontra no mesmo diretório deste README.

### Execução

Em um terminal ou janela de comando, navegue até o diretório raiz de projeto `MLND-Capstone` (que contém este README) e execute os seguintes comandos:

```bash
ipython notebook boston_housing_PT.ipynb
```  
ou
```bash
jupyter notebook boston_housing_PT.ipynb
```
Isso abrirá o o software e arquivo de projeto Jupyter Notebook em seu navegador.

### Dados
O conjunto de dados consiste em três arquivos: ratings.csv, movies.csv e links.csv. Os arquivos se encontram no mesmo diretório deste README e também podem ser encontrados na página do [MovieLens](https://grouplens.org/datasets/movielens/).

- **ratings.csv** contém 100004 entradas de dados e 4 atributos.
	- `userId`: ID do usuário
	- `movieId`: ID do filme classificado pelo usuário
	- `rating`: Nota do usuário para o filme. Em escala de 5 estrelas, com incrementos de meia (0.5) estrela
	- `timestamp`: Horário da classificação em formato timestamp

- **movies.csv** contém 9125 entradas de dados e 3 atributos.
	- `movieId`: ID do filme
	- `title`: Nome do filme
	- `genres`: Gênero do filme

- **links.csv**	contém 9125 entradas de dados e 3 atributos.
	- `movieId`: ID do filme
	- `imdbId`: ID para buscar informações na API do IMDb
	- `tmdbId`: ID para buscar informações na API do TMDb
