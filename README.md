# ConversorDeMoeda_EJ
 Programa para estágio 
 
 Código desenvolvido para avaliação de estágio. 
 
 Foi pedido para que eu fizesse um conversor de moedas de 3 moedas (dolar, euro e peso ARG) em detrimento da do Real .
 Fiz o uso das bibliotecas request e regex como foi pedido na entrevista.
 
 Basicamente eu me utilizei de uma API que atualiza as cotações das moedas a cada 30 min.
 Apenas pondo as moedas desejadas juntamente como o link da requisição , me foi retornado um dicionário python com diversas referete às moedas citadas, incluindo a cotação atual .
 
 Transformei o dicionário em uma string , para que eu pudesse tratar com regex
 
 isolando os 3 valores da moeda , e transformando - os para valores float,, realizei uma pequena formatação e prints para que ficasse apresentável no terminal
