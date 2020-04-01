# Estratificação de dados multi-label com a biblioteca Scikit-multilearn 

A capacidade de classificar e reconhecer certos tipos de dados vem sendo exigida em diversas aplicações modernas e, principalmente, onde o Big Data é usado para tomar todos os tipos de decisões, como no governo, na economia e na medicina. As tarefas de classificação também permitem que pesquisadores consigam lidar com a grande quantidade de dados as quais têm acesso.

Existe uma biblioteca, chamada Scikit-multilearn, que permite realizar diversas operações, mediante as implementações nativas do Python encontradas na biblioteca de métodos populares da classificação *multi-label*. A implementação da estratificação iterativa do Scikit-multilearn visa fornecer uma distribuição equilibrada das evidências das classes de um conjunto de dados até uma determinada ordem. 

Neste projeto, analisamos o que isso significa utilizando como conjunto de dados o conjunto de treino desbalanceado disponível na competição [Toxic Comment Classification do Kaggle](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge). Esta competição trata de um problema de classificação de texto, mais precisamente de classificação de comentários tóxicos. 

Os dados possuem um grande número de comentários do Wikipédia, classificados de acordo com os seguintes rótulos:

- toxic
- sever_toxic
- obscene
- threat
- insult
- identity_hate

Para mais informações sobre esse projeto, clique [aqui](https://insightlab.ufc.br/blog/). 

