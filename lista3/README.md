# Trabalho Final - Predição do Numero de passageiros de uma Linha Aérea - LSTM

**Docente: ADRIAO DUARTE DORIA NETO**

**Discente: Efrain Marcelo Pulgar Pantaleon**


## Introdução

A inteligência artificial e a aprendizagem de maquina profunda permitiram que diversas áreas do conhecimento dessem um grande avanço no nível das pesquisas.Com essa visão em mente, durante a  disciplina ministrada pelo professor 

Nesta ultima atividade da disciplina, foi proposto que 
apresentemos uma aplicação com o uso de técnicas de 
Inteligência Artificial abordadas durante a disciplina.Com isso, o trabalho escolhido a ser abordado será as predições do numero de passageiros para uma companhia aérea em um determinado mês.

## Palavras Chaves

Deep-Learning, Machine Learning, Airline Passenger Prediction, LSTM, Predictions, Neural Networks , Tensor Flow, Keras , Airline.

## Fundamentação Teórica

- Redes Neurais Artificiais:

São técnicas computacionais que 
apresentam um modelo matemático inspirado na estrutura 
neural de organismos inteligentes e que adquirem 
conhecimento através da experiência. Uma grande rede neural 
artificial pode ter centenas ou milhares de unidades de 
processamento; já o cérebro de um mamífero pode ter muitos 
bilhões de neurônios. Uma rede neural artificial é composta 
por várias unidades de processamento, cujo funcionamento é 
bastante simples. Essas unidades, geralmente são conectadas 
por canais de comunicação que estão associados a determinado 
peso. As unidades fazem operações apenas sobre seus dados 
locais, que são entradas recebidas pelas suas conexões. O 
comportamento inteligente de uma Rede Neural Artificial vem 
das interações entre as unidades de processamento da rede.

![Estrutura de uma Rede Neural Artificial](https://cerebromente.org.br/n05/tecnologia/image11.gif)

- Processo de  Aprendizado:

Um ponto de grande importância das redes neurais é a 
habilidade de aprender de seu ambiente e com isso melhorar 
seu desempenho. Isso é feito através de um processo 
iterativo de ajustes aplicado a seus pesos, o treinamento. O 
aprendizado ocorre quando a rede neural atinge uma solução 
generalizada para uma classe de problemas.

- Redes Neurais Long Short Term Memory (LSTM):

A LSTM é uma arquitetura de rede neural recorrente (RNN) que 
“lembra” valores em intervalos arbitrários. A LSTM é bem 
adequada para classificar, processar e prever séries 
temporais com intervalos de tempo de duração desconhecida. A 
insensibilidade relativa ao comprimento do gap dá uma 
vantagem à LSTM em relação a RNNs tradicionais (também 
chamadas “vanilla”), Modelos Ocultos de Markov (MOM) e 
outros métodos de aprendizado de sequências.

![Arquitetura LSTM](https://www.deeplearningbook.com.br/wp-content/uploads/2019/08/lstmcell.png)

## Aplicação

Para este projeto foi usado um dataset de uma companhia aérea encontrado [aqui](./AirPassengers.csv).Nele temos 2 colunas uma com as datas (dados temporais), e outra coluna referente ao numero de  passageiros correspondente a data.

Como estamos trabalhando com sequencias e predições de dados temporais, então a escolha da arquitetura LSTM é muito bem vinda.

O projeto foi desenvolvido dentro desse repositório encontrado [aqui](./trabalho_final.ipynb)

## Conclusões



## Bibliografia

- Sutton, R. S. and Barto, A. G. Introduction to reinforcement learning. MIT Press, 1998.

- van Hasselt, H., Guez, A., and Silver, D. Deep reinforcement
learning with double Q-learning.

- Tutorial: Deep Reinforcement Learning David Silver, Google DeepMind

