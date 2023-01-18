# Curry Company analysis project

This repository contains files and script to build a company strategy dashboard. This script was created during the Comunidade DS data analysis course, in order to learn how to use python for data analysis.

## The Business Problem
The Cury Company is a technology company that created an application that connects restaurants, delivery men and people.
Through this application, it is possible to order a meal, in any registered restaurant, and have it delivered at the comfort of your home by a delivery person also registered in the Cury Company application.
The company conducts business between restaurants, delivery drivers, and people, and generates a lot of data about deliveries, types of orders, weather conditions, delivery drivers' ratings, etc. Although the delivery is growing, in terms of deliveries, the CEO does not have complete visibility into the company's growth KPIs.
You have been hired as a Data Scientist to create data solutions for delivery, but before you train algorithms, the company's need is to have the key strategic KPIs organized in a single tool, so that the CEO can consult and make simple but important decisions.
The Cury Company has a business model called Marketplace, which intermediates the business between three main customers: Restaurants, deliverers, and buyers. To track the growth of this business, the CEO would like to see the following growth metrics:

### On the business side:
- Amount of orders per day;
- Number of orders per week;
- Distribution of orders by traffic type;
- Comparison of order volume by city and traffic type;
- The amount of orders per deliverer per week;
- The central location of each city by traffic type.

### On the deliveryman side:
- The lowest and highest age of the deliverers;
- The worst and best condition of vehicles;
- The average rating per delivery person;
- The average rating and standard deviation by traffic type;
- The average rating and standard deviation by weather conditions;
- The 10 fastest delivery drivers by city
- The 10 slowest deliverers by city.

### On the restaurant side:
- The amount of unique deliverers;
- The average distance from restaurants and delivery locations;
- The average delivery time and standard deviation by city;
- The average delivery time and standard deviation by city and order type;
- The average delivery time and standard deviation by city and type of traffic;
- The average delivery time during Festivals.
  
## Objective

 - The goal of this project is to create a set of charts and tables that display these metrics in the best way possible so that the CEO can have clarity of the data and make his decisions.

## Assumptions made for the analysis
- The analysis was performed with data between 11/02/2022 and 06/04/2022.
- Marketplace was the assumed business model.
- The 3 main business views were: Order transaction view, restaurant view and delivery man view.

## Solution Strategy
The strategy dashboard was developed using the metrics that reflect the 3 main views of the company's business model, being:
	1 Company growth view;
	2 Vision of the restaurants' growth;
	3 Vision of the deliverers' growth.
  
## Each view is represented by the following set of metrics:
1. Company growth view;
	- Orders per day;
	- Percentage of orders by traffic conditions;
	- Number of orders by type and by city;
	- Orders by week;
	- Number of orders by delivery type;
	- Number of orders by traffic conditions and city type.
  
2. View of the restaurants' growth
	- Number of unique orders
	- Average distance traveled;
	- Average delivery time during festival and normal days;
	- Standard deviation of delivery time during festivals and normal days;
	- Average delivery time by city
	- Distribution of average delivery time by city;
	- Average delivery time by order type.
  
3. View of the growth of the delivery drivers
	- Age of the oldest and youngest delivery person
	- Evaluation of the best and worst vehicle;
	- Average evaluation per delivery person
	- Average assessment by traffic conditions;
	- Average assessment by weather conditions;
	- Average time of the fastest delivery person;
	- Average time of the fastest delivery person per city.

## The Top 3 Data Insights
1.	The seasonality of the number of orders is daily. There is approximately a 10% variation in the number of orders on sequential days;
2.	Semi-Urban type cities do not have low traffic conditions;
3.  The biggest variations in delivery time, happen during sunny weather.

## The final product of the project
- Online dashboard, hosted in a Cloud and available for access from any internet connected device.
The panel can be accessed through this link: 

## Conclusion
- The goal of this project is to create a set of graphs and tables that display these metrics to best help the CEO's decision making.
According to the data from the Company view, we can conclude that the number of orders grew between week 06 and week 13 of the year 2022.

## Future steps for the project:
- Reduce the number of metrics.
- Create new filters.
- Add new business views.

------------------------------------------------------------------------
Este repositório contém documentos e scripts para construir um painel de estratégia da empresa. Este script foi criado durante o curso de Análise de Dados da Comunidade DS, a fim de aprender a utilizar o python para análise de dados.

## O Problema de negócio
A Cury Company é uma empresa de tecnologia que criou um aplicativo que conecta restaurantes, entregadores e pessoas.
Através desse aplicativo, é possível realizar o pedido de uma refeição, em qualquer restaurante cadastrado, e recebê-lo no conforto da sua casa por um entregador também cadastrado no aplicativo da Cury Company.
A empresa realiza negócios entre restaurantes, entregadores e pessoas, e gera muitos dados sobre entregas, tipos de pedidos, condições climáticas, avaliação dos entregadores e etc. Apesar da entrega estar crescento, em termos de entregas, o CEO não tem visibilidade completa dos KPIs de crescimento da empresa.
Você foi contratado como um Cientista de Dados para criar soluções de dados para entrega, mas antes de treinar algoritmos, a necessidade da empresa é ter um os principais KPIs estratégicos organizados em uma única ferramenta, para que o CEO possa consultar e conseguir tomar decisões simples, porém importantes.
A Cury Company possui um modelo de negócio chamado Marketplace, que fazer o intermédio do negócio entre três clientes principais: Restaurantes, entregadores e pessoas compradoras. Para acompanhar o crescimento desses negócios, o CEO gostaria de ver as seguintes métricas de crescimento:

### Do lado da empresa:
- Quantidade de pedidos por dia;
-	Quantidade de pedidos por semana;
-	Distribuição dos pedidos por tipo de tráfego;
- Comparação do volume de pedidos por cidade e tipo de tráfego;
-	A quantidade de pedidos por entregador por semana;
-	A localização central de cada cidade por tipo de tráfego.

### Do lado do entregador:
-	A menor e maior idade dos entregadores;
-	A pior e a melhor condição de veículos;
-	A avaliação médida por entregador;
-	A avaliação média e o desvio padrão por tipo de tráfego;
-	A avaliação média e o desvio padrão por condições climáticas;
-	Os 10 entregadores mais rápidos por cidade;
- Os 10 entregadores mais lentos por cidade.

### Do lado do restaurantes:
-	A quantidade de entregadores únicos;
-	A distância média dos resturantes e dos locais de entrega;
-	O tempo médio e o desvio padrão de entrega por cidade;
-	O tempo médio e o desvio padrão de entrega por cidade e tipo de pedido;
-	O tempo médio e o desvio padrão de entrega por cidade e tipo de tráfego;
-	O tempo médio de entrega durantes os Festivais.
  
## Objetivo

 - O objetivo desse projeto é criar um conjunto de gráficos e tabelas que exibam essas métricas da melhor forma possível para o CEO poder ter clareza dos dados e tomar suas decisões.

## Premissas assumidas para a análise
-	A análise foi realizada com dados entre 11/02/2022 e 06/04/2022.
-	Marketplace foi o modelo de negócio assumido.
-	As 3 principais visões do negócio foram: Visão transação de pedidos, visão restaurante e visão entregadores.

## Estratégia da solução
O painel estratégico foi desenvolvido utilizando as métricas que refletem as 3 principais visões do modelo de negócio da empresa, sendo:
	1	Visão do crescimento da empresa;
	2	Visão do crescimento dos restaurantes;
	3	Visão do crescimento dos entregadores.
  
Cada visão é representada pelo seguinte conjunto de métricas:
1. Visão do crescimento da empresa;
	- Pedidos por dia;
	- Porcentagem de pedidos por condições de trânsito;
	- Quantidade de pedidos por tipo e por cidade;
	- Pedidos por semana;
	- Quantidade de pedidos por tipo de entrega;
	- Quantidade de pedidos por condições de trânsito e tipo de cidade.
  
2. Visão do crescimento dos restaurantes
	- Quantidade de pedidos únicos;
	- Distância média percorrida;
	- Tempo médio de entrega durante festival e dias normais;
	- Desvio padrão do tempo de entrega durante festivais e dias normais;
	- Tempo de entrega médio por cidade;
	- Distribuição do tempo médio de entrega por cidade;
	- Tempo médio de entrega por tipo de pedido.
  
3. Visão do crescimento dos entregadores
	- Idade do entregador mais velho e do mais novo;
	- Avaliação do melhor e do pior veículo;
	- Avaliação média por entregador;
	- Avaliação média por condições de trânsito;
	- Avaliação média por condições climáticas;
	- Tempo médido do entregador mais rápido;
	- Tempo médio do entregador mais rápido por cidade.

## O Top 3 Insights de dados
1.	A sazonalidade da quantidade de pedidos é diária. Há uma variação de aproximadamente 10% do número de pedidos em dia sequenciais;
2.	As cidades do tipo Semi-Urban não possuem condições baixas de trânsito;
3.  As maiores variações no tempo de entrega, acontecem durante o clima ensoladao.

## O produto final do projeto
- Painel online, hospedado em um Cloud e disponível para acesso em qualquer dispositivo conectado à internet.
O painel pode ser acessado através desse link: 

## Conclusão
- O objetivo desse projeto é criar um conjunto de gráficos e tabelas que exibam essas métricas que ajudem da melhor forma possível a tomada de decisão do CEO.
De acordo com os dados da visão da Empresa, podemos concluir que o número de pedidos cresceu entre a semana 06 e a semana 13 do ano de 2022.

## Passos futuros para o projeto:
-	Reduzir o número de métricas.
-	Criar novos filtros.
-	Adicionar novas visões de negócio.
