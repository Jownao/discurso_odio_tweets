# Hate Speech on Twitter Data

Repositório contendo conjunto de dados utilizados para análise de discurso de ódio com base rótulada e treinada utilizando Support Vector Machine (SVM). Esse projeto faz parte do estudo realizado para o meu trabalho prático da disciplina de Big Data Analysis de Ciências da Computação na Universidade Tiradentes (UNIT).

Foi feito esse estudo com base nos tweets coletados utilizando a API do twitter atráves do meu trabalho de conclusão de curso disponível [aqui](https://github.com/Jownao/tweet_polarity_analysis) onde é possível ver todos métodos de pré-processamento utilizados bem como a forma que feito o treinamento para que se chegasse ao conjunto final de dados utilizados aqui nesse estudo.

A apresentação referente a esse trabalho se encontra neste link do [canva](https://www.canva.com/design/DAFltu664CA/iCy7qRuw0pmEV0GHSccxpQ/view).

### Objetivos

##### Geral
Realizar uma análise de discurso de ódio em tweets coletados durante a manifestação em Brasília, com o objetivo de compreender a prevalência, padrões e impactos desse discurso.

##### Específicos
Para alcançar o objetivo geral, delineiam-se os seguintes objetivos específicos compreendidos nesse projeto:

* Classificar os tweets em categorias, identificando aqueles que contêm discurso de ódio ou não utilizando técnicas de processamento de linguagem natural e aprendizado de máquina através da biblioteca do Spark - NLP.
* Analisar a frequência do discurso de ódio nos tweets, identificando padrões e tendências relacionadas à manifestação em Brasília;
* Identificar as principais palavras-chave e termos utilizados no discurso de ódio durante o evento;
* Encontrar as palavras mais utilizadas a cada tipo de rótulo;


### Estruturação do repositório

```
|- datasets
  |- tweets_trabalho.xlsx
|- LICENSE
|- README.md
|- Trabalho_pratico_2UN.ipynb

```

### Dicionário do dataset

- **text:**  Este campo contém o texto original extraído por meio da API, sem ter passado por nenhum processo de pré-processamento ou remoção de informações irrelevantes.
- **clean_text:**  Neste campo, encontra-se o texto que passou por um processo de pré-processamento, no qual foram removidas informações irrelevantes para a análise.






