# StockPred

StockPred é um projeto de análise de dados históricos financeiros e valores de papeis negociadas na B3 (bolsa de valores brasileira).
O projeto consiste em analisar e explorar os dados com o intuito de serem utilizados para tomada de decisões e até mesmo para o uso de técnicas de Machine Learning para predição de resultados.

Atualmente os dados estão sendo fornecidos por planilhas e arquivos csv. 

Dados ttilizados como features:
  * Balanços Financeiros (período de 10 anos)
  * Demonstrativos do Resultado do Exercício (período de 10 anos)
Dados utilizados como label:
  * Valores históricos do papel da empresa especifica (período de 10 anos)
    * Valores diários, semanais e mensais.

Obs.: StockPred é um projeto paralelo ao projeto StockData no qual é resposável pela extração, transformação e carregamento de dados (ETL).
Os dados coletados pelo StockData serão posteriormente utilizados pelo StockPred.
