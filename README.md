# Regressão Logística

##Sobre

Este projeto consiste em aplicar um modelo de Machine Learning em uma base de dados da área médica para a disciplina de Redes Complexas. Para isto, escolheu-se para o modelo o classificador Regressão Logística e a base de dados sobre o Cancer Cervical.

A base de dados foi obtida em: https://archive.ics.uci.edu/ml/datasets/Cervical+Cancer+Behavior+Risk

O código foi escrito em Python 3 na plataforma Google Colaboratory.

## Requisitos

- Google Colaboratory ou Jupyter Notebook

## Metodologia

O trabalho foi dividido em quatro etapas:
  * Aquisição da base de dados;
  * Pré-processamento;
  * Treinamento do Modelo;
  * Validação do Modelo.
  
Os dados foram obtidos no repositório UCI de Machine Learning. Obteu-se uma base de dados sobre o Cancer Cervical, que contém as seguites características: 72 instâncias, 19 atributos e todos do tipo Inteiro, e a tarefa associada é classificação.

Na etapa de pré-processamento, verificou-se se havia campos de atributos vazios e fez-se a normalização dos dados.

Na etapa de treinamento, utilizou-se da classe GridSearch da biblioteca do SKLearn. Em resumo, o GridSearch é uma classe que implementa funções para buscar melhores parâmetros para a base de dados, utilizando a validação cruzada para cada parâmetro.

Na etapa de validação do modelo pode-se comparar os resultados do modelo na fase de treinamento e teste. Verificou-se que o classificador obteve resultados semelhantes, em que obteve score de 93% no treinamento e 94% no teste.
