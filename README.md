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



<img width="1272" height="794" alt="Captura de tela 2026-03-27 132120" src="https://github.com/user-attachments/assets/58d700fe-41fb-47b0-85b4-96d178889fd3" />


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

## Alguns pontos que chamaram atenção:

* Entregas com atraso superior a 4 dias apresentaram uma queda bem relevante na avaliação média (≈4,2 → 1,8), mostrando o impacto direto na experiência do cliente
* Estados como MA e AL concentraram as maiores taxas de atraso (~25%), o que pode indicar gargalos logísticos regionais
* Em agosto, houve um aumento expressivo de cancelamentos concentrados em pedidos via voucher, sugerindo um possível desalinhamento entre incentivos comerciais e a capacidade operacional
* Cartão de crédito concentra ~77% do faturamento, indicando uma baixa diversificação nos meios de pagamento

---

## 📸 Imagens do Dashboard

### 🔹 Capa


<img width="1441" height="796" alt="Captura de tela 2026-03-24 230131" src="https://github.com/user-attachments/assets/7483ab4c-81d0-4596-b807-c417644970b5" />


### 🔹 Visão Geral


<img width="1443" height="811" alt="Captura de tela 2026-03-25 004633" src="https://github.com/user-attachments/assets/4f1a58c4-f915-49ac-9bd4-216be0b59c84" />


### 🔹 Logística & Experiência


<img width="1442" height="808" alt="Ecommerce logistica" src="https://github.com/user-attachments/assets/0456f871-f1ba-48df-b0c8-14da93b124b7" />



### Visão Detalhada


<img width="1435" height="801" alt="Captura de tela 2026-03-25 004701" src="https://github.com/user-attachments/assets/fab87663-2373-4edf-a8c0-bc1150668940" />



### 🔹 Produtos & Sellers


<img width="1446" height="808" alt="Captura de tela 2026-03-25 004715" src="https://github.com/user-attachments/assets/15642094-383d-4195-88a2-528e8ed3f5f7" />


### 🔹 Financeiro


<img width="1445" height="811" alt="Captura de tela 2026-03-27 132022" src="https://github.com/user-attachments/assets/fbcbcf92-17bc-4283-89e5-f47a52e87c4d" />


---

## 📌 Observações

Os dados utilizados são públicos e o projeto foi desenvolvido para fins de estudo, prática de modelagem e composição de portfólio.

