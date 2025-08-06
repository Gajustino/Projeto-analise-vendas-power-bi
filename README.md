# Power BI Dashboard — Faturamento, Lucro e Vendas por Região

Este projeto foi desenvolvido com o objetivo de analisar, visualizar e apresentar de forma clara e interativa os principais indicadores comerciais de uma empresa: **Faturamento**, **Lucro**, **Devoluções** e **Vendas**.

Utilizei o Power BI para transformar os dados brutos em um painel executivo moderno e funcional, permitindo uma leitura rápida por parte de tomadores de decisão.

---

##  Link público

[Clique aqui para visualizar o Dashboard no Power BI](https://app.powerbi.com/view?r=eyJrIjoiMWE4NWQzZjAtMWQ1My00MzY5LWEyZTMtMTAxN2I1ZDcyMmZlIiwidCI6Ijc5YzcwOGI2LWRkODMtNDgwYS04ZDNkLTI5YTYyZTg3N2IyMSJ9)

---

## Objetivo

Criar um dashboard interativo para facilitar o monitoramento de desempenho financeiro, comercial e geográfico da empresa, com foco em:

- Faturamento e lucro total
- Análise por produtos, marcas e canais de venda
- Vendas por país e continente
- Identificação de produtos mais lucrativos
- Comparações por ano (2020–2022)

---

## Ferramentas utilizadas

- **Power BI Desktop**
- Segmentações hierárquicas, drill-through e filtros dinâmicos
- Parâmetros de campo para alternância de métricas
- Gráficos de barras, linhas, mapas geográficos, árvore de decomposição e KPIs

---

## Funcionalidades e Destaques

### Página 1 – **Visão Geral**
- KPI Cards com Faturamento, Lucro, % de Devoluções e Perda de Faturamento
- Gráfico de colunas + linha mostrando a evolução mensal de Faturamento x Lucro
- Segmentação por ano (2020, 2021, 2022)
- Gráfico de **Top 15 produtos mais lucrativos**
- Lucro por Marca e Canal de Venda

### Página 2 – **Árvore de Produto**
- Análise hierárquica de **Marca → Categoria → Produto**
- Drill automático até o nível de produto com valor de faturamento em cada nível
- Botão de alternância entre "Lucro Total" e "Faturamento Total" via **parâmetro de campo**

### Página 3 – **Países e Lojas**
- Tabela detalhada com **país, faturamento, lucro e número de vendas**
- Gráfico de barras com os **15 países com maior volume de vendas**
- **Mapa interativo** com a distribuição das lojas pelo mundo

---

## Organização do Modelo

- **Tabelas Fato**: `Vendas`, `Devoluções`
- **Tabelas Dimensão**: `Clientes`, `Produtos`, `Lojas`, `Calendário`
- **Tabelas de Medidas Organizadas** em pastas: `Medidas Vendas`, `Medidas Faturamento`, `Medidas Devoluções`
- Parâmetro de campo: `Parâmetro Lucro/Faturamento`

---

## Insights Relevantes (exemplos)

- O canal de vendas **físico** representou a maior parte do lucro.
- Alguns **produtos premium** como notebooks e iPhones concentram grande parte do faturamento.
- A empresa possui maior concentração de lojas e vendas na **Europa e Ásia**.
- Países como **Alemanha e China** lideram em volume e lucro.
- A árvore de decomposição mostrou que **Apple e Asus** estão entre as marcas mais rentáveis.

---

## Próximos Passos

- Criar bookmarks com visão comparativa por ano
- Inserir tooltip customizado com evolução temporal por marca
- Adicionar segmentação por faixa de preço dos produtos
- Publicar versão pública via Power BI Service (opcional)

