# Hidden Markov Models

utiliza a distribuicao de probabilidades para prever o futuro


estados: sao dados relativos as labels, os estados são "escondidos"(hidden), pois eles não são utilizados no treinamento por ser um  modelo nao supervisionado

observacoes: cada caso isolado de probabilidade associado a um estado (dados a serem usados)

transicoes:  a probabilidade de um novo estado acontecer, ou seja a previsao se um estado vai mudar ou nao em um futuro proximo


# exemplo: previsao do tempo

## estados:
dia quente (S1)
dia frio/chuvoso (S2)

## transicoes:
dia 1 ser quente e dia 2 ser frio   : 20% de chance 
dia 1 ser quente e dia 2 ser quente : 80% de chance 
dia 1 ser frio e dia 2 ser quente   : 30% de chance 
dia 1 ser frio e dia 2 ser frio     : 70% de chance 

## observacoes:

dia quente
mean(media de temperatura): 20
min(temperatura minima)   : 15
max(temperatura maxima)   : 25


dia chuvoso
mean(media de temperatura): 5
min(temperatura minima)   : -5
max(temperatura maxima)   : 15

obs: esses dados das observacoes sao pegos em distribuicoes normais, onde o mean (media) e o pointo do meio/alto da curva, e o min e max sao o ponto mais a esquerda e mais a direita respectivamente no grafico

