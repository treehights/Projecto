| Nome da coluna        | Significado           | Possíveis valores  |
| ------------- |:-------------:| -----:|
| `data` | Data a que se referem os dados | DD-MM-YYYY |
| `recebidas` | Número total de doses de vacinas recebidas | Inteiro >= 0 ou _vazio_ |
| `distribuidas` | Número total de doses de vacinas distribuidas | Inteiro >= 0 ou _vazio_ |
| `[*]` | As colunas seguintes referem-se aos valores para Portugal continental, sem sufixo, e repetindo depois com cada sufixo por idade [0_17, 18_24, 25_49, 50_64, 65_79, 80+, desconhecido], e por ARS [arsnorte, arscentro, arslvt, arsalentejo, arsalgarve, madeira, açores, outro] |
| `doses` | Número total de doses de vacinas administradas | Inteiro >= 0 ou _vazio_ |
| `doses_novas` | Número diário de doses de vacinas administradas | Inteiro >= 0 ou _vazio_ |
| `doses1` | Número total de primeiras doses de vacinas administradas | Inteiro >= 0 ou _vazio_ |
| `doses1_novas` | Número diário de primeiras doses de vacinas administradas | Inteiro >= 0 ou _vazio_ |
| `doses2` | Número total de segundas doses de vacinas administradas | Inteiro >= 0 ou _vazio_ |
| `doses2_novas` | Número diário de segundas doses de vacinas administradas | Inteiro >= 0 ou _vazio_ |
| `dosesunk` | Número total de doses desconhecidas de vacinas administradas | Inteiro >= 0 ou _vazio_ |
| `dosesunk_novas` | Número diário de doses desconhecidas de vacinas administradas | Inteiro >= 0 ou _vazio_ |
| `doses1_perc` | Percentagem de população vacinada com a primeira dose | fracção entre [0, 1] ou _vazio_ |
| `doses2_perc` | Percentagem de população vacinada com a segunda dose | fracção entre [0, 1] ou _vazio_ |
| `populacao1` | População a que se referem os dados (doses1 ÷ doses1_perc), a que deverá corresponder ao respectivo valor de população de acordo com INE/PORDATA 2019 | Inteiro >= 0 ou _vazio_ |
| `populacao2` | População a que se referem os dados (doses2 ÷ doses2_perc), a que deverá corresponder ao respectivo valor de população de acordo com INE/PORDATA 2019 | Inteiro >= 0 ou _vazio_ |

Relativamente ao ficheiro `data_concelhos.csv`:
