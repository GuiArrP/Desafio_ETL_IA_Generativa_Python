# Explorando IA Generativa em um Pipeline de ETL com Python

Esse desafio foi iniciado no ano de 2023 para o Santander [BootCamp 2023 - Ciência de Dados com Python](https://web.dio.me/track/santander-bootcamp-2023-ciencia-de-dados-com-python) disponibilizado pela [DIO](https://www.dio.me/) durante o perido de Agosto a Outubro de 2023.

## 🎯 Objetivo

O objetivo desse desafio é utilizar uma [API](https://github.com/digitalinnovationone/santander-dev-week-2023-api) desenvolvida pela DIO para criar mensagens de marketing personalizadas para cada cliente.

1. Para meu objetivo ser cumprido como cientista de dados foi fornecido a mim um arquivo .csv simples com uma lista de ids dos usuários do banco.

    ~~~~python
    UserID
    1
    2
    3
    4
    5
    ~~~~

2. Consumindo o endpoint `GET https://sdw-2023-prd.up.railway.app/users/{id}` (API da Santander Dev Week 2023) para obter dados de cada cliente.

3. Tendo os dados de cada um dos clientes será usada a API do ChatGPT (OpenAI) para a geração de mensagens de marketing personalizada para cada cliente, enfantizando a importancia dos investimentos.

4. Assim que essas mensagens estiverem prontas as mesmas serão amarzenadas na API na lista "news" de cada usuário usando a endpoint `PUT https://sdw-2023-prd.up.railway.app/users/{id}`.

## ❗Observação

Esse reposítorio foi feito com base nas aulas preparatorias para o desafio, portanto boa parte do conteudo foi elaborado durante a aula do professor [Venilton Falvo Jr](https://www.linkedin.com/in/falvojr/).
