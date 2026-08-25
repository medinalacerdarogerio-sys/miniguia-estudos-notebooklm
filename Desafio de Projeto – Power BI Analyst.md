# Desafio de Projeto – Power BI Analyst

## Descrição do Projeto

Neste desafio foi desenvolvido um relatório utilizando o **Power BI**, com base na amostra de dados financeiros disponibilizada para o curso.

O objetivo principal foi aplicar os conhecimentos adquiridos na criação de relatórios e dashboards, realizando a importação e organização dos dados, criação de medidas e construção de visualizações para facilitar a análise das informações.

A base utilizada contém dados relacionados a vendas, produtos, segmentos, países, unidades vendidas, descontos, custos e lucros.

## Desenvolvimento

Durante a realização do projeto, foram trabalhados os seguintes pontos:

- Importação da base de dados **Financial Sample**;
- Organização e tratamento das informações no Power BI;
- Criação de medidas utilizando **DAX**;
- Análise de vendas;
- Análise de unidades vendidas;
- Análise de descontos e custos;
- Análise de lucro;
- Criação de gráficos interativos;
- Utilização de filtros e segmentações de dados;
- Organização visual dos dashboards para facilitar a interpretação das informações.

## Medidas Criadas

Foram utilizadas medidas para calcular os principais indicadores do relatório:

```DAX
Total Vendas =
SUM(financials[Sales])

Total Unidades Vendidas =
SUM(financials[Units Sold])

Total Descontos =
SUM(financials[Discounts])

Total COGS =
SUM(financials[COGS])

Total Lucro =
SUM(financials[Profit])

Margem de Lucro =
DIVIDE(
    [Total Lucro],
    [Total Vendas],
    0
)
```

## Estrutura do Relatório

O projeto foi organizado em páginas de análise, permitindo visualizar diferentes perspectivas dos dados.

### Página 1 – Relatório de Vendas

Nesta página foram apresentados indicadores e gráficos relacionados a:

- Total de vendas;
- Unidades vendidas;
- Total de descontos;
- Custo dos produtos vendidos;
- Vendas por período;
- Vendas por segmento;
- Vendas por produto;
- Vendas por país.

### Página 2 – Análise de Lucro

Nesta página foram desenvolvidas visualizações para análise de:

- Lucro total;
- Lucro por ano;
- Lucro por país;
- Lucro por segmento;
- Lucro por período.

### Página 3 – Análise Complementar

Como complemento ao relatório, foi criada uma página com uma visão mais ampla dos resultados, incluindo:

- Vendas por país;
- Unidades vendidas por país;
- Lucro por país;
- Distribuição do lucro por segmento.

## Tecnologias Utilizadas

- Power BI Desktop;
- Power Query;
- Linguagem DAX;
- Excel como fonte de dados.

## Conclusão

A realização deste desafio permitiu colocar em prática os conhecimentos fundamentais de Power BI, desde a importação e organização dos dados até a criação de medidas e dashboards interativos.

O projeto possibilitou transformar uma base de dados financeiros em informações visuais mais claras e objetivas, facilitando a análise de vendas, custos, descontos e lucros.

O resultado final foi um conjunto de dashboards interativos que permite explorar os dados por diferentes dimensões, como **produto, segmento, país e período**.

Base de dados e materiais de referência disponibilizados no repositório do curso:

[Repositório Power BI Analyst](https://github.com/julianazanelatto/power_bi_analyst?utm_source=chatgpt.com)