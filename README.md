# Pós-Graduação Estácio | Big Data, Analytics e bi Aplicados Aos Negócios



## 📋 Contexto

A empresa contratante chama-se Adventure Works (AW). A contratante é uma indústria de bicicletas em franco crescimento que se orgulha de possuir mais de 500 produtos distintos, 20.000 clientes e 31.000 pedidos. Para manter seu ritmo de crescimento e se diferenciar da concorrência, a Adventure Works quer utilizar seus dados de forma estratégica, norteando suas decisões para se tornar uma empresa data driven. A diretoria da Adventure Works já listou uma série de perguntas que ela quer responder através de cruzamentos dos dados, e que devem guiar o desenvolvimento. 

### 🔧 Perguntas para serem respondidas:

- a) Qual o número de pedidos, quantidade comprada, valor total negociado por produto, tipo de cartão, motivo de venda, data de venda, cliente, status, cidade, estado e país?
- b) Quais os produtos com maior ticket médio por mês, ano, cidade, estado e país? (ticket médio = Faturamento bruto - descontos do produto / número de pedidos no período de análise)
- c) Quais os 10 melhores clientes por valor total negociado filtrado por produto, tipo de cartão, motivo de venda, data de venda, status, cidade, estado e país?
- d) Quais as 5 melhores cidades em valor total negociado por produto, tipo de cartão, motivo de venda, data de venda, cliente, status, cidade, estado e país?
- e) Qual o número de pedidos, quantidade comprada, valor total negociado por mês e ano (dica: gráfico de série de tempo)?
- f) Qual produto tem a maior quantidade de unidades compradas para o motivo de venda “Promotion”?

### ⚙️ Descrição dos dados
A Adventure Works possui um banco de dados transacional (PostgreSQL) que armazena os dados de suas diferentes áreas. Esses dados estão distribuídos em 68 tabelas divididas em 5 schemas: HR (recursos humanos), sales (vendas), production (produção) e purchasing (compras).


## ⌨️ Entregas 

* Diagrama conceitual do data warehouse: Modelo conceitual com as tabelas de fatos e dimensões necessárias para responder às perguntas de negócio. 

* Configuração e transformações de dados: DBT.
    - 1) **Documentação das tabelas e colunas nos marts**
    - 2) **Testes de sources**
    - 3) **Testes nas primary keys das tabelas de dimensão e fatos**
    - 4) **Teste de dados**
    - 5) **O código precisa estar em um repositório (github).**

* Painéis de BI: Responder as perguntas feitas anteriormente.

## 🛠️ Construído com:

* [DBT](https://docs.getdbt.com/) - Ferramenta de transformação de Dados
* [GoogleBigQuery](https://cloud.google.com/bigquery?hl=pt-br) - Data Warehouse em Nuvem
* [PowerBI](https://learn.microsoft.com/pt-br/power-bi/) - Ferramenta de BI.

## ✒️ Autor

* **Raphael Caetano da Silva** - *Analytics Engineering*
