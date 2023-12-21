[![author](https://img.shields.io/badge/author-jaomarcelofc-red.svg)](https://www.linkedin.com/in/joao-marcelo-fonseca-cunha) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/)

# Análise de Dados de Sensores IoT em Tempo Real com Apache Spark Streaming e Apache Kafka

<p align="center">
  <img src= "imagens/kafka.png"width=50% >
</p>

<p align="center">
  <img src= "imagens/sparkstreaming.jpg"width=50% >
</p>

# Definição do Problema e Fonte de Dados
Neste projeto vamos implementar uma solução completa de análise de dados em tempo real usando o Apache Spark e o Apache Kafka. Vamos coletar dados de sensores IoT (Internet of Things) e, em tempo real (à medida que os dados são gerados e coletados), realizar o trabalho de análise e entregar a resposta para um determinado problema de negócio.

Este projeto é composto de diversas partes uma vez que toda a infraestrutura necessária será construída passo a passo. 

# Simulador IOT

Para coletar dados dos sensores IoT (Internet of Things), vamos seguir as seguintes etapas:

**1-	Abrir o terminal ou prompt de comando e acessar a pasta com o simulador.**

2-	Execute o comando abaixo para gerar um arquivo com 10.000 leituras de sensores IoT (pode gerar quantos registros você desejar).
