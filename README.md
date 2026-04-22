# 🛠️ Desafio SQL: Sistema de Gerenciamento de Oficina Mecânica
> **Bootcamp Heineken/DIO:** Inteligência Artificial Aplicada a Dados com Copilot.

Este repositório apresenta a solução completa para o desafio de modelagem e implementação de um banco de dados para controle de uma oficina mecânica. O projeto simula o fluxo operacional real, desde o cadastro do cliente e veículo até a emissão de ordens de serviço (OS) e controle de peças.

---

## 🎯 Objetivo do Projeto
Estruturar um banco de dados relacional robusto capaz de gerenciar:
- **Clientes e Veículos:** Relação de propriedade e histórico.
- **Ordens de Serviço (OS):** Controle de status, data de emissão e previsão de entrega.
- **Mão de Obra e Peças:** Composição de custos de serviços realizados por mecânicos especializados.
- **Tabela de Referência:** Cálculo de serviços baseado em tabelas de preços e horas trabalhadas.

---

## 📂 Estrutura do Repositório

- **`SCRIPT DE TABELAS`**: Definições DDL (Data Definition Language) para criação de toda a estrutura relacional.
- **`INSERÇÃO DE DADOS`**: Scripts DML (Data Manipulation Language) para popular o banco e validar as relações.
- **`ATIVIDADE_OFICINA-2025-03-02...png`**: Diagrama Entidade-Relacionamento (DER) que detalha a arquitetura do banco.
- **`SCRIPTS DE CONSULTA`**: Arquivo contendo 11 consultas SQL complexas focadas em KPIs operacionais.
- **`Query1.png` a `Query11.png`**: Screenshots evidenciando os resultados das consultas executadas.

---

## 🧠 Lógica de Modelagem
O banco foi desenhado para garantir a integridade dos dados através de chaves primárias e estrangeiras, permitindo a rastreabilidade total de qual mecânico realizou determinado serviço em qual veículo, e quais peças foram utilizadas.

---

## 📊 KPIs e Consultas Realizadas
As 11 queries desenvolvidas respondem a perguntas críticas para a gestão de uma oficina, tais como:
- **Custo Total por OS:** Soma de peças e mão de obra.
- **Desempenho por Mecânico:** Quantidade de serviços atribuídos e realizados.
- **Filtragem Estratégica:** Identificação de serviços pendentes ou veículos de marcas específicas.
- **Análise de Agregados:** Uso de `GROUP BY` e `HAVING` para identificar os serviços mais rentáveis.

---

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** SQL.
- **Engine:** MySQL / PostgreSQL.
- **Modelagem:** Diagramação técnica de banco de dados.

---

## 👨‍💻 Autor
**Denis Comitre** *IT Operations Leader | Especialista em Dados & IA*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/denis-comitre/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Comitre-D)

---
> **Nota:** Este projeto demonstra a aplicação de lógica relacional para otimização de fluxos operacionais e suporte à tomada de decisão em serviços técnicos.
