# Simulação de Detecção de Metais Pesados e Microplásticos no Oceano

Este projeto consiste em uma simulação para detecção de metais pesados e microplásticos no oceano, utilizando leituras geradas aleatoriamente e processadas por um script em Python. A simulação demonstra como sensores podem fornecer leituras variáveis, as quais são posteriormente analisadas para verificar se os níveis de metais pesados e microplásticos excedem os limites de segurança predefinidos. O código simula o comportamento dos sensores e interpreta os dados gerados, fornecendo uma visão clara de como tais sistemas podem ser utilizados para monitorar a qualidade da água.

## Requisitos

É necessário possuir um conhecimento básico em Python ou em lógica de programação para entender o funcionamento do projeto.

## Dependências

É necessário possuir um software editor de código, como o Visual Studio Code, para executar o projeto.

## Objetivos do Projeto

- Gerar valores aleatórios que representam leituras de metais pesados e microplásticos no oceano.
- Verificar quantas dessas leituras excedem os limites de segurança estabelecidos.
- Exibir um relatório indicando o número de vezes que os limites de segurança foram excedidos, emitindo alertas apropriados.

## Explicação do Código

1. Definimos os limites de segurança para cada material:
   - 0,05 mg/L para os metais.
   - 100 partículas/L para os microplásticos.

2. Utilizamos a função `random` para gerar leituras de cada material, onde os valores estão dentro das médias estabelecidas:
   - Para os metais, as leituras estão no intervalo entre 0 e 0.1 mg/L.
   - Para os microplásticos, as leituras estão no intervalo entre 50 e 150 partículas/L.

3. Relatamos os dados da simulação e emitimos alertas quando os limites são ultrapassados, incluindo:
   - A quantidade de leituras que foram realizadas (50 como exemplo no código).
   - O número de vezes que os limites de cada material foram excedidos.


