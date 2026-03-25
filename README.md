# 📊 E-Commerce Analytics | Power BI

## 🧠 Sobre o projeto

Este projeto tem como objetivo desenvolver um modelo analítico completo para um e-commerce, permitindo análises de vendas, logística, pagamentos e satisfação dos clientes.

O foco foi aplicar boas práticas de **modelagem dimensional** e construir uma base escalável para dashboards no Power BI.

---

## 🎯 Perguntas de negócio

- Qual o impacto dos atrasos na satisfação do cliente?
- Quais categorias geram mais receita?
- Existe relação entre tipo de pagamento e cancelamento?
- Quais sellers apresentam melhor performance logística?

---

## 💡 Principais Insights

- Pedidos com atraso apresentaram menor avaliação média dos clientes
- Cartão de crédito representa a maior parte do faturamento
- Algumas categorias concentram grande volume de vendas, mas baixa margem
- Há sellers com alto volume de vendas, porém com maior taxa de atraso

---

## 🏗️ Modelagem de Dados

O modelo segue o padrão **Star Schema**, com separação entre tabelas fato e dimensões:

### 🔹 Tabelas Fato

* `FT_PEDIDOS` → nível de pedido
* `FT_ITEMPEDIDO` → nível de item
* `FT_PAGAMENTOS` → pagamentos por pedido
* `FT_REVIEW` → avaliações dos clientes

### 🔹 Dimensões

* `DIM_CLIENTES`
* `DIM_PRODUTOS`
* `DIM_VENDEDOR`
* `DIM_CALENDARIO`

---

## 📊 KPIs Monitorados

* 💰 **Faturamento total**
* 🛒 **Total de pedidos**
* 📦 **Total de itens vendidos**
* 🎯 **Ticket médio**
* ❌ **Pedidos cancelados**
* 🚚 **Entregas no prazo**
* ⏱️ **Atraso médio**
* 📅 **Tempo médio de entrega**
* 🧩 **Receita por categoria**
* 🏪 **Receita por seller**
* 💳 **Receita por tipo de pagamento**
* ⚠️ **Pedidos em risco de atraso**

---

## 🛠️ Ferramentas Utilizadas

*  **Power BI**
*  **Power Query (M)**
*  **DAX**
*  **Modelagem Dimensional (Star Schema)**

---

## 🧠 Principais Aprendizados

*  Entendimento de **granularidade** entre pedidos, itens e pagamentos
*  Construção de **medidas DAX com análise temporal**
*  Uso do **Power Query** para tratamento e padronização de dados
*  Desenvolvimento de dashboards com foco **analítico e operacional**

---

## 📸 Imagens do Dashboard

### 🔹 Capa
<img width="1441" height="796" alt="Captura de tela 2026-03-24 230131" src="https://github.com/user-attachments/assets/7483ab4c-81d0-4596-b807-c417644970b5" />

### 🔹 Visão Geral

<img width="1443" height="806" alt="Captura de tela 2026-03-24 230949" src="https://github.com/user-attachments/assets/77deb8e6-f79a-4808-9396-d04b1129f623" />

### 🔹 Logística & Experiência


<img width="1442" height="810" alt="Captura de tela 2026-03-24 231112" src="https://github.com/user-attachments/assets/2a8720b8-6656-4869-a41f-0cf2ef0f5517" />


### Visão Detalhada


<img width="1499" height="761" alt="Captura de tela 2026-03-24 231209" src="https://github.com/user-attachments/assets/12cf7e30-cf7f-4a08-a859-c537260de02d" />


### 🔹 Produtos & Sellers


<img width="1442" height="808" alt="Captura de tela 2026-03-24 232600" src="https://github.com/user-attachments/assets/ee051d10-f230-4555-8d77-8478f04e1c30" />


### 🔹 Financeiro


<img width="1445" height="811" alt="Captura de tela 2026-03-24 232645" src="https://github.com/user-attachments/assets/9b91e6a4-1c44-46b7-bcb6-7858b4fb9e06" />


---

## 📌 Observações

Os dados utilizados são públicos e o projeto foi desenvolvido para fins de estudo, prática de modelagem e composição de portfólio.

