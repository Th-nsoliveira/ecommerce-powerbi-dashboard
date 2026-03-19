# Brazilian E-Commerce Power BI Dashboard

## Overview
Projeto de análise de dados desenvolvido em Power BI com foco em vendas, logística, financeiro, produtos, sellers e monitoramento operacional de pedidos.

## Objetivo
Construir um dashboard gerencial para apoiar a tomada de decisão em um contexto de e-commerce, permitindo acompanhar indicadores de performance comercial, financeira e logística.

## Principais análises
- Visão geral de vendas
- Logística e experiência do cliente
- Produtos e sellers
- Financeiro
- Monitoramento de pedidos em andamento

## Modelagem de dados
O modelo foi estruturado com base em tabelas fato e dimensão, respeitando a granularidade de pedidos, itens e pagamentos.

### Tabelas fato
- FT_PEDIDOS
- FT_ITEMPEDIDO
- FT_PAGAMENTOS

### Dimensões
- DIM_CALENDARIO
- DIM_CLIENTES
- DIM_PRODUTOS
- DIM_VENDEDORES

## KPIs monitorados
- Faturamento total
- Total de pedidos
- Total de itens vendidos
- Ticket médio
- Pedidos cancelados
- Entregas no prazo
- Atraso médio
- Tempo médio de entrega
- Receita por categoria
- Receita por seller
- Receita por tipo de pagamento
- Pedidos em risco de atraso

## Ferramentas utilizadas
- Power BI
- Power Query
- DAX
- Modelagem dimensional

## Principais aprendizados
- Diferença de granularidade entre pedidos, itens e pagamentos
- Construção de medidas DAX com comparação temporal
- Uso de Power Query para tratamento e padronização de dados
- Criação de dashboards com foco analítico e operacional

## Imagens do dashboard
### Visão Geral
![Visão Geral](docs/imagens/overview.png)

### Logística & Experiência
![Logística](docs/imagens/logistica.png)

### Produtos & Sellers
![Produtos & Sellers](docs/imagens/produtos-sellers.png)

### Financeiro
![Financeiro](docs/imagens/financeiro.png)

### Monitoramento Operacional
![Monitoramento](docs/imagens/monitoramento.png)

## Como abrir o projeto
1. Baixe o arquivo `.pbix`
2. Abra no Power BI Desktop
3. Atualize as conexões de dados, se necessário

## Observações
Os dados utilizados são públicos e o projeto foi desenvolvido para fins de estudo, prática de modelagem e composição de portfólio.
