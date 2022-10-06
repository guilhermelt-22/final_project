# Projeto Final Ironhack

  Status do Projeto: Completo

# Objetivo do Projeto

  Este projeto tem como objetivo, a partir de dados anteriores à partida, prever o resultado de partidas de futebol

# Métodos Utilizados

  - Estatística 
  - Machine Learning
  - Transformação de Dados 
  - Limpeza de Dados

# Tecnologias 

  - Python
    - Pandas
    - Numpy
    - Pycaret

# Descrição do Projeto

 Utilizando o dataset da Premier League da season de 2018/2019 (link: https://footystats.org/download-stats-csv#) e as ferramentas de modelagem da biblioteca Pycaret, foi feita a criação de um modelo que prevê o resultado de partidas de futebol. Os resultados estão catalogados como: 1(vitória ou empate) e 0(derrota), sendo estes resultados da perspectiva do time mandante     
  

# Passos
  
  - Importação da bibliotecas Pycaret, Numpy e Pandas
  - Importação do dataset escolhido
  - Seleção das  colunas que possuam informações estatísticas sobre os times durante o jogo 
  - Criação da coluna resultado: 1(vitoria ou empate) e 0(derrota)
  - Separação das colunas sobre o time mandante e visitante
  - Crianção de funções que calculam a média das estatístias anteriores á partida de cada time 
  - Adição dessas estatísticas no dataset
  - Criação de funções contabilizam vitórias, empates e derrotas recentes dos times que estão jogando 
  - Seleção das colunas 'Pre-Match PPG (Home)','Pre-Match PPG (Away)','home_team_goal_count','away_team_goal_count' e 'resultado', pois se mostraram as mais relevantes para a modelagem
  - Utilização do modelo KNN, pois após a tunagem se demonstrou o com melhor desempenho
  - Criação da pipeline no Pycaret 
  - Transformação do modelo em arquivo .pkl para poder reutilizar em outras situações 

# Conclusão
  
  Ao final do projeto o modelo foi capaz de prever os resultados com uma acurácia de ~0.74 e um F1 score de ~0.83 

# Contact
  
  Linkedin: https://www.linkedin.com/in/guilhermeteofilo/
  Github: https://github.com/guilhermelt-22