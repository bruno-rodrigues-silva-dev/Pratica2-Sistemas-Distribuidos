# Prática 2 – Sistemas Distribuídos

## AVA2 – Implementação de algoritmos de comunicação e sincronização distribuída

**Aluno:** Bruno Rodrigues da Silva  
**Disciplina:** Plataformas e Sistemas de Alto Desempenho  
**Professora:** Ana Paula Faragó  
**Instituição:** Universidade Veiga de Almeida (UVA)  
**Ano:** 2026

## Sobre o projeto

Este projeto apresenta uma simulação de um sistema distribuído desenvolvida em Python, utilizando comunicação por Sockets TCP, threads e mensagens no formato JSON.

A implementação demonstra conceitos fundamentais de sistemas distribuídos, por meio da comunicação entre um servidor coordenador e três processos.

## Funcionalidades implementadas

- Comunicação entre processos utilizando Sockets TCP.
- Serviço de nomes para registro dos processos.
- Chamadas remotas de procedimento (RPC).
- Relógios lógicos de Lamport.
- Simulação simplificada de eleição de coordenador pelo algoritmo Bully.
- Sincronização do estado global.
- Confirmação de recebimento por mensagens ACK.

## Tecnologias utilizadas

- Python 3
- Google Colab
- Sockets TCP
- Threads
- JSON

## Execução

O código pode ser executado em uma única célula do Google Colab.

1. Abra o notebook do projeto.
2. Execute a célula de código.
3. Aguarde a inicialização do servidor e dos três processos.
4. Acompanhe no console as operações RPC, a eleição do coordenador e a sincronização do estado global.

## Resultados

Na execução apresentada, foram obtidos os seguintes resultados:

- Processo 1: 2 × 3 = 6.
- Processo 2: 4 × 5 = 20.
- Processo 3: 6 × 7 = 42.
- Resultado global: 68.
- Coordenador eleito: Processo 3.
- Confirmações recebidas: 3/3 ACKs.

## Arquivo do projeto

O notebook Python está disponível neste repositório no formato `.ipynb`.

## Autor

Bruno Rodrigues da Silva  
Engenharia da Computação – Universidade Veiga de Almeida (UVA)
