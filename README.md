# 📊 PROJETO IPCA - ETL E ANÁLISE DE DADOS  

## 📌 Contexto e Motivação  

Nosso cliente, o **Banco IP2CA**, é uma instituição financeira consolidada no mercado brasileiro de varejo, com **20 anos de atuação** e uma base de **50 milhões de clientes ativos**.  

Como um banco altamente impactado pela variação do **Índice de Preços ao Consumidor Amplo (IPCA)**, o IP2CA enfrenta desafios para reagir rapidamente às mudanças econômicas devido a processos **lentos e manuais** na captura e análise desse índice.  

Para solucionar essa dor, o cliente solicitou uma **análise detalhada do IPCA desde sua fundação**, com a geração de **insights estratégicos** que possam apoiar a tomada de decisões e otimizar a gestão do negócio.  

## 🎯 Objetivo  

Desenvolver um **pipeline de dados** automatizado para processar e analisar o **IPCA dos últimos 20 anos**, permitindo ao Banco IP2CA obter insights rápidos e acionáveis por meio de visualizações interativas no **Power BI**.  

## 🛠️ Tecnologias Utilizadas  

- **Databricks**: Pipeline de Dados
- **Pyspark**: Processamento e tratamento dos Dados
- **Power BI**: Análise e visualização de dados  

## 🔍 Escopo do Projeto  

✔️ Criar um pipeline eficiente para ingestão e transformação dos dados do IPCA  
✔️ Analisar a evolução do índice desde a fundação do Banco IP2CA  
✔️ Construir visualizações interativas para facilitar a interpretação dos dados  
✔️ Identificar padrões e tendências que possam impactar as decisões estratégicas do cliente  

## 📌 Requisitos

## Coleta de Dados

   ✔️ Utilizar a API de Dados Abertos do Banco Central do Brasil para coletar os dados do IPCA dos últimos 20 anos.
   ✔️ A documentação da API pode ser acessada em: [Banco Central - IPCA](https://dadosabertos.bcb.gov.br/dataset/10844-indice-de-precos-ao-consumidor-amplo-ipca---servicos/resource/c0980df7-ad92-47af-b71c-790825f4710a)
  
## Processamento e Armazenamento

  ✔️ Criar um notebook no Databricks para processar os dados utilizando Python ou SQL.
  ✔️ Armazenar os dados do IPCA e os resultados das análises em tabelas Delta Lake dentro do Databricks.
  
## Análise e Visualização

  ✔️ Criar um relatório no Power BI Desktop

