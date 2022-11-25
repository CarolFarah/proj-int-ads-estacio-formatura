# Projeto de Engenharia/Ciência de Dados com integração entre SQL Server e Microsoft Power BI simulando situação real para avaliação semestral da matéria de Proj. Int. Análise de Sistemas da Universidade Estácio de Sá.

Projeto Acadêmico de Conclusão de Curso
- Instituição: Universidade Estácio de Sá
- Campus: Recreio/BW
- Professor: Raphael Jesus
- Semestre: 2022.2

Membros do grupo:

- Ana Carolina de Oliveira Farah / matrícula 201803355093
- Henrique Moura de Mesquita / matrícula 201803355085

Tema e propósito:
- Construir um processo de migração de cargas de trabalho para Data Lake a partir de um dataset com relatório de vendas da Pocco Pamonhas
- Realizar etapas de tratamentos necessárias
- Modelar dados e construir Data Warehousing
- Exibir visão dos KPI's através de Dashboard interativo

Tecnologias utilizadas:

- Databricks
- Data Factory
- Power BI
- IaaS / Cloud Azure
- Infraestrutura pay as you go
- Framework pySpark
- Biblioteca pandas
- Linguagens SQL e Python 3.10
- ETL com Arquitetura Medalhão (Bronze, Prata e Gold)

### Foi utilizado star schema (Tabelas Fatos e Dimensões) e Data Warehousing integrado do Power BI.

## Criação das tabelas Fatos e Dimensões - star schema

![alt text](https://i.imgur.com/7l0W81n.png)

## Criação da Procedure - 1a. Parte

![alt text](https://i.imgur.com/DBESZhJ.png)

## Criação da Procedure - 2a. Parte

![alt text](https://i.imgur.com/LqzgbQv.png)

## Exibição da tabela Fatos

![alt text](https://i.imgur.com/Fstlk4G.png)

## Etapas de Data Integration - Amostra de parte do código fonte
*Para procedimentos detalhados, efetuar o download do código fonte na pasta Databricks

![alt text](https://i.imgur.com/n2qHODK.png)

## Etapas de Data Integration - Amostra de parte do código fonte
*Para procedimentos detalhados, efetuar o download do código fonte na pasta Databricks

![alt text](https://i.imgur.com/JtRe5Qp.png)

## Orquestação realizada no Azure Data Factory

![alt text](https://i.imgur.com/64zSNhY.png)

## Overview do Dashboard de exibição dos dados

![alt text](https://i.imgur.com/QTWDr2u.png)

Filtros e cards utilizados:

- Card de lucro total
- Card de receita total
- Card de receita total dos últimos 30 dias
- Card de receita total dos últimos 10 dias
- Card de unidades totais vendidas
- Mapa mundial com amostras do tipo bolhas vinculadas ao volume da receita total por país e região
- Gráficos de colunas empilhadas para receitas totais dos últimos 30 dias e dos últimos 10 dias
- Filtro por canais de vendas
- Filtro por data
