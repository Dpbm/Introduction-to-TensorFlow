# Clustering

algoritmo de aprendizado nao supervisionado (entregamos dados que nao possuem labels para o modelo)

o modelo encontra onde os dados se agrupam no grafico




# K-means

1. escolhe pontos quaisquer no grafico para serem os centroids(k pontos quaisquer, lembrando que esses pontos quaisquer nao sao necessariamente pontos de dados, mas sim coordenadas aleatorias do grafico)
2. depois cada dado ve a distancia euclidiana dele ate todos os centroids, e assim aquele que for mais perto pertencera ao cluster daquele centroid
3. agora os centroids serao movidos para onde possuem mais pontos em seus relativos clusters (conhecido como centro de massa)
4. repete os dois passos acima ate que os pontos nao mudem de lugar


obs: as labels serao dadas aos centroids