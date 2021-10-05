# CNPQ
Projeto de Iniciação Científica
Este projeto tem como finalidade criar Mecanismo Para Identificação de Imagens Submetidas a GANs (Generative Adversarial Networks).


Introdução
A GAN, conhecida como (Generative Adversarial Network) possuí uma excelente capacidade de produzir imagens falsas através de imagens reais, usando duas funções: Generative, que produz imagens idênticas a imagens verídicas e um Discriminative, que objetiva o encontro de variações resultante do Generative. Utilizou-se o modelo Cyclegan que por sua vez não necessita reconhecer dados de entradas, além de aprender a mapear características em comum entre uma imagem de entrada e uma de saída, para alcançar resultados satisfatórios, no entanto o resultado contém diversas imperfeições (ruídos). Os ruídos são um grande problema nas análises entre imagens, pois impossibilita obter uma acurácia significativa, todavia utilizou-se de um modelo Noise2Noise baseado em regressão em CNN (Convolutional Neural Network) que possuí o intuito de remover tais ruídos, tornando em imagens mais nítidas.


Objetivo
Busca-se criar um mecanismo que identifique imagem produzida por GAN, a fim de mitigar os efeitos negativos proporcionado por este modelo, a exemplo Deep Fakes.


Materiais e Método
O estudo propôs identificar imagem submetida a GAN, para tanto utilizou-se do modelo Cyclegan para obtenção das imagens, como também o modelo Noise2Noise para remoção dos ruídos contidos nas imagens, bem como de uma ferramenta chamada Opencv que dispõe de diversos modelos para análise de imagens, pelo qual usufruiu-se do Histograma representando a distribuição dos pixels através de um gráfico.


Resultados
Os resultados mostraram-se promissores principalmente nas imagens sem ruídos, no entanto não foi possível obter uma acurácia elevada. Em certos momentos pode-se averiguar algo em torno de 10% para imagens sem ruídos sobre imagens contendo ruídos.


Considerações finais
Conclui-se que o estudo realizado atingiu o objetivo. No entanto, as análises realizadas não alcançaram um resultado exímio, todavia este trabalho contribui para o desenvolvimento de ferramentas voltadas a segurança computacional, como também ao que se diz respeito a detecção de anomalias em imagens através dos métodos aqui citados. O presente estudo abordou as características resultantes de uma imagem buscando aprender a criar uma imagem cada vez mais próxima de uma imagem real. Analisou-se que as melhores amostras foram obtidas em torno de 50 epochs de treinamento. Adiante sofreram distorções regressando o resultado visual indicativo de imagens submetidas a GAN.



Palavras chave: Generative Adversarial Network; Deep Fake; Noise2Noise; Convolutional Neural Network
