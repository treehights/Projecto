# Dados Relativos aos Top Hits no Spotify (2000-2019)



**Última actualização:** 30 de maio de 2022

Conjunto de dados das músicas do Top Hits do Spotify entre 2000 e 2019. Dados que recolhemos no dia 11 de junho de 2022 em [link kaggle](https://www.kaggle.com/datasets/paradisejoy/top-hits-spotify-from-20002019), disponíveis em songs_normalize.csv.

Fonte dos dados: www.kaggle.com


# Contexto

A indústria da música tem vindo a crescer e desenvolvemos este projeto para perceber melhor as preferências musicais do mundo, a evolução dos gêneros musicais ao longo dos anos e quais os artistas que se destacam através da análise do Top Hits do Spotify. 
Estes dados também podem vir a ser relevantes para entender o crescimento da própria aplicação em termos de usuários, que se pode refletir no número de vezes que os Top Hits foram escutados. Pode ser útil para saber quais são os artistas mais populares neste período de tempo, saber se há mais Top Hits com ou sem conteúdo explicito,etc.



# Estrutura

O repositório está organizado da seguinte forma:

**Spotify Top Hits 2000 - 2019.ipynb:** Ficheiro Jupyter Notebook Python com código de processamento de análise do Top Hits do Spotify entre 2000 e 2019. 

**songs_normalize.csv:** contém o conjunto de dados em formato csv.
**Readme.md:** Breve descrição do projecto


# API

Os API's usados são:
import numpy as np # Álgebra linear
import pandas as pd 
import matplotlib.pyplot as plt # Visualização
import seaborn as sns # Visualização baseada no matplotlib
import plotly.express as px # Visualização

# Dicionário dos Dados

Uma explicação do conteúdo em "songs_normalize.csv".

| Nome da coluna        | Significado           |
| ------------- |:-------------:|
| "artist" |  Nome do artista | 
| "song" |  Nome da faixa | 
| "duration_ms" | Duração da faixa em milissegundos |
| "explicit" | A letra ou o conteúdo de uma música que contém um ou mais dos critérios que podem ser considerados ofensivos ou inadequados para crianças |
| "year" | Ano de lançamento da faixa |
| "popularity" | Quanto mais alto for o valor, mais popular é a música |
| "danceability" | Descreve quão adequada é uma faixa para dançar com base numa combinação de elementos musicais, incluindo tempo, estabilidade do ritmo, força da batida, e regularidade geral. Um valor de 0,0 é menos dançável e 1,0 é mais dançável |
| "energy" | É uma medida de 0,0 a 1,0 e representa uma medida perceptual de intensidade e actividade |
| "key" | A nota da música. Por exemplo 0 = C, 1 = C♯/D♭, 2 = D, e assim por diante. Se nenhuma nota foi detectada, o valor é -1 |
| "loudness" | O ruído geral de uma música em decibéis (dB). Os valores de ruído são calculados, em média, e são úteis para comparar o ruído relativo das músicas. A sonoridade é a qualidade de um som que é a principal correlação psicológica da força física (amplitude). Os valores variam tipicamente entre -60 e 0 db |
| "mode" | Indica a escala (maior ou menor) de uma faixa. O tipo de escala da qual deriva o seu conteúdo melódico. A maior é representada por 1 e a menor é 0 |
| "speechiness" | Detecta a presença de palavras faladas numa música. Quanto mais a gravação é falada (por exemplo, talk show, livro áudio, poesia), mais próximo de 1,0 o valor do atributo. Valores acima de 0,66 descrevem faixas que são provavelmente feitas inteiramente de palavras faladas. Valores entre 0,33 e 0,66 descrevem faixas que podem conter tanto música como fala, quer em secções ou em camadas, incluindo casos como a música rap. Os valores abaixo de 0,33 representam muito provavelmente música e outras faixas que não tenham fala. |
| "acousticness" | Medida entre 0,0 e 1,0, que representa se a música é acústica ou não |
| "instrumentalness" | Prevê se uma faixa não contém vocais. Neste contexto, os sons "Ooh" e "aah" são tratados como instrumentais. As faixas de rap ou de palavras faladas são claramente "vocais". Quanto mais próximo o valor instrumental for de 1,0, maior a probabilidade de a faixa não conter qualquer conteúdo vocal. Valores acima de 0,5 destinam-se a representar faixas instrumentais. |
| "liveness" | Detecta a presença de um público na gravação. Valores mais elevados representam uma maior probabilidade de que a música tenha sido executada ao vivo. Um valor acima de 0,8 fornece uma forte probabilidade de que a faixa seja executada ao vivo |
| "valence" | Uma medida de 0,0 a 1,0 que representa a positividade musical transmitida por uma faixa. Músicas com valência alta soam mais positivas (felizes, alegres, eufóricas), enquanto faixas com valência baixa soam mais negativas (tristes, deprimidas, zangadas). |
| "tempo" | O tempo global estimado de uma faixa em batidas por minuto (BPM). Em terminologia musical, tempo é a velocidade ou ritmo de uma determinada peça e deriva directamente da duração média da batida |
| "genre" | Género da música |



# Bibliografia




https://www.kaggle.com/datasets/paradisejoy/top-hits-spotify-from-20002019

https://matplotlib.org/3.5.0/index.html

https://seaborn.pydata.org/index.html

https://stackoverflow.com/

https://pandas.pydata.org/docs/index.html
