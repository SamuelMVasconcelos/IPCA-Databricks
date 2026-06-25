# 📊 PROJETO IPCA - ETL E ANÁLISE DE DADOS  

## 📌 Contexto e Motivação  

Nosso cliente, o **Banco IP2CA**, é uma instituição financeira consolidada no mercado de varejo brasileiro, com **20 anos de atuação** , e cerca de **50 milhões de clientes ativos**.

Por ser fortemente influenciado pelas variações do **Índice de Preços ao Consumidor Amplo (IPCA)**, o banco enfrenta dificuldades para responder com agilidade às mudanças econômicas, principalmente devido a processos **manuais e lentos** na coleta e análise desse indicador.

Diante desse cenário, o cliente solicitou uma **análise completa do IPCA desde 2006**, com o objetivo de gerar **insights estratégicos** que auxiliem na tomada de decisões e contribuam para uma gestão mais eficiente do negócio.

## 🎯 Objetivo  

Desenvolver um **pipeline de dados** automatizado para processar e analisar o **IPCA dos últimos 20 anos**, permitindo ao Banco IP2CA obter insights rápidos e acionáveis por meio de visualizações interativas no **Power BI**.  

## 🛠️ Tecnologias Utilizadas  

- **Databricks Community**: Criação Pipeline de Dados
- **Python**: Linguagem utilizada para criação do código
- **SQL**: Linguagem para gerenciamento do Banco de Dados
- **Pandas**: Processamento e tratamento dos Dados
- **Power BI**: Análise e visualização de dados  

## 🔍 Escopo do Projeto  

- Criar um pipeline eficiente para ingestão e transformação dos dados do IPCA  
- Analisar a evolução do índice desde a fundação do Banco IP2CA  
- Construir visualizações interativas para facilitar a interpretação dos dados  
- Identificar padrões e tendências que possam impactar as decisões estratégicas do cliente  

## 📌 Requisitos

## Coleta de Dados

  - Utilizar a API de Dados Abertos do Banco Central do Brasil para coletar os dados do IPCA dos últimos 20 anos.
  - A documentação da API pode ser acessada em: [Banco Central - IPCA](https://dadosabertos.bcb.gov.br/dataset/10844-indice-de-precos-ao-consumidor-amplo-ipca---servicos/resource/c0980df7-ad92-47af-b71c-790825f4710a)
  
## Processamento e Armazenamento

  - Criar um notebook no Databricks para processar os dados utilizando Python ou SQL.
  - Armazenar os dados do IPCA e os resultados das análises em tabelas Delta Lake dentro do Databricks.
  
## Análise e Visualização

  - Criar um relatório no Power BI Desktop


## 📊 Sobre o Dashboard

   O dashboard foi criado para fornecer uma visão da variação do IPCA ao longo do tempo, destacando tendências, médias e padrões. Ele inclui os seguintes elementos:

## KPIs Principais

 - IPCA Ano Atual: Exibe o índice acumulado no ano atual.
   
 - Média IPCA Últimos 12 Meses: Apresenta a média mensal do IPCA no último ano.
   
 - Média IPCA Últimos 5 Anos: Mostra a média do IPCA nos últimos 5 anos.
   
 - Desvio Padrão do IPCA: Mede a volatilidade do índice ao longo do período analisado.

## Gráfico de Linha - Evolução do IPCA Anual

   Exibe a evolução do IPCA acumulado ao longo dos meses para cada ano dos últimos 20 anos, permitindo comparações históricas e identificação de padrões sazonais.

## Filtros Interativos

 - Período de Análise: Permite alternar entre diferentes períodos (Ano Atual, Últimos 3 Anos, Últimos 5 Anos, Últimos 10 Anos e Todos os Anos).
   
 - Seleção de Ano: Possibilita a escolha de um ano específico para análise detalhada.

<img width="1380" height="803" alt="{C9C6F9ED-4168-40C4-827A-A8B8A744F18B}" src="https://github.com/user-attachments/assets/55ace885-dea1-4cf2-b73e-0eeba0b88cf8" />






## 📊 Tendências e Padrões

✔️ Queda Recente: O IPCA do ano atual está em 2,18, significativamente menor que o do ano anterior (5,84), representando um queda de 267,8%.

✔️ Desvio Padrão Relativamente Baixo (0,35) indica que a variação do IPCA ao longo do tempo não tem sido tão extrema.

✔️ Os meses de Dezembro, Janeiro e Fevereiro são os meses onde o IPCA teve as maiores Altas. 
