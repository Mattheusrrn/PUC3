# Brasileirão Analytics
# 1.0 Objetivo
O objetivo deste trabalho é analisar fatores e variáveis que podem influenciar o desempenho das equipes no Brasileirão. Através de análises, diversas perguntas pertinentes ao desempenho dos clubes serão melhor entendidas:

Desempenho Fora de Casa: O desempenho do clube jogando fora de casa pode ser um determinante para a conquista do campeonato?

Desempenho em Casa: O desempenho dentro de casa tem um impacto significativo na conquista do campeonato?

Desempenho de Campeões Anteriores: Os campeões de temporadas anteriores conseguem manter o alto nível de desempenho no ano seguinte, ou geralmente apresentam uma queda significativa?

Impacto do Fator Estadual: O desempenho das equipes é influenciado pelo estado de origem? Times de determinados estados têm vantagens ou desvantagens específicas?

Este estudo pretende oferecer uma visão abrangente e detalhada sobre como esses fatores interagem e influenciam os resultados das equipes no Brasileirão, utilizando dados estatísticos para apoiar as conclusões


# 2.0 Coleta

A coleta foi feita no site da kaggle: https://www.kaggle.com/datasets/ricardomattos05/jogos-do-campeonato-brasileiro


# 3.0 Modelagem
|Atributos | Descrição |
|----------|-----------|
|datetime | Data e horário do jogo: 2012-06-06 20:30:00 - 2022-11-13 16:00:00 |
|home_team|	Clube mandante |
|home_team_state | Estado do Clube |
|away_team | Clube visitante |
|away_team_state | Estado |
|home_goal | Quantos Gols o mandante fez: 0-6 gols |
|away_goal|	Quantos Gols o visitante fez: 0-6 gols |
|season | Temporada 2012-2022 |
|round| Rodada 1-38 |

Como é apenas 1 arquivo, então não houve necessidade de uma descrição complexa da modelagem.

# 4.0 Modelagem
O upload feito diretamente no Databricks através do DBFS.
![image](253181e3-70f7-469a-8e87-2f8334d9106d.jfif)
