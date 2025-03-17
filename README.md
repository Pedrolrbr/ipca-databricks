# 📊 PROJETO IPCA - ETL E ANÁLISE DE DADOS  

## 📌 Contexto e Motivação  

Nosso cliente, o **Banco IP2CA**, é uma instituição financeira consolidada no mercado brasileiro de varejo, com **20 anos de atuação** e uma base de **50 milhões de clientes ativos**.  

Como um banco altamente impactado pela variação do **Índice de Preços ao Consumidor Amplo (IPCA)**, o IP2CA enfrenta desafios para reagir rapidamente às mudanças econômicas devido a processos **lentos e manuais** na captura e análise desse índice.  

Para solucionar essa dor, o cliente solicitou uma **análise detalhada do IPCA desde sua fundação**, com a geração de **insights estratégicos** que possam apoiar a tomada de decisões e otimizar a gestão do negócio.  

## 🎯 Objetivo  

Desenvolver um **pipeline de dados** automatizado para processar e analisar o **IPCA dos últimos 20 anos**, permitindo ao Banco IP2CA obter insights rápidos e acionáveis por meio de visualizações interativas no **Power BI**.  

## 🛠️ Tecnologias Utilizadas  

- **Databricks Community**: Criação Pipeline de Dados
- **Python**: Linguagem utilizada para criação do código
- **SQL**: Linguagem para gerenciamento do Banco de Dados
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


## 📊 Sobre o Dashboard

   O dashboard foi criado para fornecer uma visão clara da variação do IPCA ao longo do tempo, destacando tendências, médias e padrões. Ele inclui os seguintes elementos:

## KPIs Principais

✔️ IPCA Ano Atual: Exibe o índice acumulado no ano atual.
   
✔️ Média IPCA Últimos 12 Meses: Apresenta a média mensal do IPCA no último ano.
   
✔️ Média IPCA Últimos 5 Anos: Mostra a média do IPCA nos últimos 5 anos.
   
✔️ Desvio Padrão do IPCA: Mede a volatilidade do índice ao longo do período analisado.

## Gráfico de Linha - Evolução do IPCA Anual

   Exibe a evolução do IPCA acumulado ao longo dos meses para cada ano dos últimos 10 anos, permitindo comparações históricas e identificação de padrões sazonais.

## Filtros Interativos

 ✔️ Período de Análise: Permite alternar entre diferentes períodos (Ano Atual, Últimos 3 Anos, Últimos 5 Anos, Últimos 10 Anos e Todos os Anos).
   
 ✔️ Seleção de Ano: Possibilita a escolha de um ano específico para análise detalhada.

![image](https://github.com/user-attachments/assets/c0b18c6f-039b-4cf2-8689-57e1e9573289)

## 📊 Tendências e Padrões

✔️ Aumento Recente: O IPCA do ano atual está em 1,6, significativamente maior que o do ano anterior (1,08), representando um aumento de 48,1%.

✔️ Médias de Longo Prazo: A média do IPCA dos últimos 5 anos (0,52) é ligeiramente maior do que a dos últimos 12 meses (0,45), indicando que o índice pode estar se estabilizando ou reduzindo no curto prazo. (Lembrete:  A média do IPCA dos últimos 5 anos Desconsidera os anos de 2020 e 2021, anos da Pandemia do Covid-19.)

✔️ Tendência de Picos no 2º Semestre: Em diversos anos, o IPCA apresenta um crescimento mais acentuado entre junho e dezembro.

✔️ 2024 e 2025 Abaixo da Média (até o momento): As linhas que representam esses anos estão posicionadas abaixo da média histórica.
