# 📊 Sistema de Gestão e Análise de Vendas com PostgreSQL

Projeto prático desenvolvido com o objetivo de aplicar conceitos de **modelagem de banco de dados relacional**, **SQL** e **Data Analytics**, utilizando o PostgreSQL para estruturar, organizar e analisar dados comerciais de uma empresa fictícia do setor de varejo.

---

## 🚀 Objetivo

Construir um banco de dados relacional capaz de:

- Armazenar informações de clientes, produtos, vendedores e pedidos  
- Permitir análises comerciais estratégicas  
- Gerar insights para apoio à tomada de decisão  

---

## 🧠 Contexto do Problema

A empresa fictícia **NovaCom Comercial** enfrentava dificuldades como:

- Falta de visibilidade sobre faturamento e desempenho  
- Dificuldade em identificar produtos mais vendidos  
- Ausência de análise de comportamento de clientes  
- Problemas no controle de estoque  

O projeto propõe resolver esses desafios por meio da estruturação e análise de dados.

---

## 🗄️ Modelagem do Banco de Dados

O banco foi estruturado com 6 tabelas principais:

- `clientes`
- `vendedores`
- `categorias`
- `produtos`
- `pedidos`
- `itens_pedido`

### 🔗 Relacionamentos

- Cliente → Pedidos (1:N)  
- Vendedor → Pedidos (1:N)  
- Categoria → Produtos (1:N)  
- Pedido → Itens (1:N)  
- Produto → Itens (1:N)  

---

## 🛠️ Tecnologias Utilizadas

- **PostgreSQL** → Banco de dados relacional  
- **SQL** → Manipulação e análise de dados  
- **pgAdmin** → Interface gráfica para gerenciamento  

---

## 📥 Etapas do Projeto

### 1. Criação do Banco

- Definição das tabelas  
- Criação de chaves primárias e estrangeiras  

### 2. Inserção de Dados

- Dados fictícios simulando ambiente real  
- Clientes, produtos, vendedores e pedidos  

### 3. Consultas SQL

- Análises com:
  - `SELECT`
  - `JOIN`
  - `GROUP BY`
  - `SUM`, `COUNT`, `AVG`

---

## 📊 Perguntas de Negócio (Business Questions)

O projeto responde a perguntas como:

- Qual o faturamento total?
- Quais produtos mais vendem?
- Quem são os melhores vendedores?
- Quais clientes geram mais receita?
- Qual o ticket médio?
- Quais produtos estão com estoque baixo?
- Qual o faturamento por mês?

---

## 📈 Principais Insights

- Identificação de produtos com maior impacto no faturamento  
- Comparação de desempenho entre vendedores  
- Identificação de clientes mais valiosos  
- Análise de categorias mais lucrativas  
- Monitoramento de estoque e reposição  

---

## 💡 Aprendizados

Este projeto permitiu desenvolver habilidades em:

- Modelagem de dados relacional  
- Escrita de consultas SQL analíticas  
- Interpretação de dados para tomada de decisão  
- Pensamento orientado a dados (Data-Driven)  

---

## 📌 Possíveis Melhorias

- Criação de um **dashboard (Power BI ou Metabase)**  
- Implementação de **índices para performance**  
- Uso de **views e procedures**  
- Inclusão de um **diagrama ER (DER)**  

---

## 📎 Como Executar

Criar o banco no PostgreSQL:

- CREATE DATABASE projeto_analytics_comercial;

- Executar os scripts SQL:

- Criação de tabelas

- Inserção de dados

- Consultas analíticas

Utilizar o pgAdmin ou outro cliente SQL para explorar os dados

---

👨‍💻 Autor

Cleiton Ferreira Hentges

---

📌 Conclusão

O projeto demonstra como o uso de PostgreSQL + SQL permite transformar dados brutos em informações estratégicas, apoiando decisões mais assertivas e orientadas por dados.
