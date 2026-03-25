# 📊 E-Commerce Analytics | Power BI

##  Sobre o projeto

Este projeto tem como objetivo desenvolver um modelo analítico completo para um e-commerce, permitindo análises de vendas, logística, pagamentos e satisfação dos clientes.

O foco foi aplicar boas práticas de **modelagem dimensional** e construir uma base escalável para dashboards no Power BI.

---

##   Perguntas de negócio

- Qual o impacto dos atrasos na satisfação do cliente?
- Quais categorias geram mais receita?
- Existe relação entre tipo de pagamento e cancelamento?
- Quais sellers apresentam melhor performance logística?

---

##   Modelagem de Dados

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

## KPIs Monitorados

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

##  Ferramentas Utilizadas

*  **Power BI**
*  **Power Query (M)**
*  **DAX**
*  **Modelagem Dimensional (Star Schema)**

---

##  Principais Aprendizados

*  Entendimento de **granularidade** entre pedidos, itens e pagamentos
*  Construção de **medidas DAX com análise temporal**
*  Uso do **Power Query** para tratamento e padronização de dados
*  Desenvolvimento de dashboards com foco **analítico e operacional**

---

## 📸 Imagens do Dashboard

### 🔹 Capa


<img width="1441" height="796" alt="Captura de tela 2026-03-24 230131" src="https://github.com/user-attachments/assets/7483ab4c-81d0-4596-b807-c417644970b5" />


### 🔹 Visão Geral


<img width="1443" height="811" alt="Captura de tela 2026-03-25 004633" src="https://github.com/user-attachments/assets/4f1a58c4-f915-49ac-9bd4-216be0b59c84" />


### 🔹 Logística & Experiência


<img width="1446" height="810" alt="Captura de tela 2026-03-25 004651" src="https://github.com/user-attachments/assets/b6b4cd5a-f867-400a-ad39-2747cee5efec" />


### Visão Detalhada


<img width="1435" height="801" alt="Captura de tela 2026-03-25 004701" src="https://github.com/user-attachments/assets/fab87663-2373-4edf-a8c0-bc1150668940" />



### 🔹 Produtos & Sellers


<img width="1446" height="808" alt="Captura de tela 2026-03-25 004715" src="https://github.com/user-attachments/assets/15642094-383d-4195-88a2-528e8ed3f5f7" />


### 🔹 Financeiro


<img width="1442" height="811" alt="Captura de tela 2026-03-25 004731" src="https://github.com/user-attachments/assets/36b4655e-2fc7-4bfe-8145-b8a80143cf85" />


---

## 📌 Observações

Os dados utilizados são públicos e o projeto foi desenvolvido para fins de estudo, prática de modelagem e composição de portfólio.

