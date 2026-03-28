# 🍔 Lanchonete Manager - Desafio Backend

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)

<img width="1916" height="1031" alt="Captura de tela 2026-03-28 102902" src="https://github.com/user-attachments/assets/0d1d5dbe-d86f-45aa-9496-df2ab6668fb5" />

<img width="1918" height="1029" alt="Captura de tela 2026-03-28 102928" src="https://github.com/user-attachments/assets/2a931423-c45a-49a1-b1c7-7a95ff75183a" />

## 📝 Sobre o Projeto
Este projeto foi desenvolvido como parte do **Desafio Técnico do Módulo Backend (M2 e N2)**. O objetivo principal é realizar a transição de um sistema de registro manual (caderno) para uma solução digital robusta utilizando **PostgreSQL**.

A solução foca na organização de clientes, produtos e pedidos, garantindo a integridade dos dados e facilitando a geração de relatórios de vendas.

## 🚀 Solução Técnica
A estrutura do banco de dados foi planejada para resolver a falta de centralização das informações, utilizando:
- **Relacionamentos 1:N** para vincular clientes a múltiplos pedidos.
- **Tabela de Itens de Pedido** para detalhamento de vendas e controle de estoque.
- **Triggers/Defaults** para automação de datas e status.

### 🛠️ Tecnologias Utilizadas
- **Banco de Dados:** PostgreSQL
- **Modelagem:** [dbdiagram.io](https://dbdiagram.io/)
- **Editor:** VS Code

## 📊 Modelagem Visual (DER)
Você pode visualizar o Diagrama Entidade-Relacionamento através do link abaixo:
🔗 [Link para o Diagrama no dbdiagram.io](COLE_AQUI_O_SEU_LINK_PUBLICO)

## 📁 Estrutura de Arquivos
- `script.sql`: Contém os comandos de criação de tabelas (DDL), inserção de dados (DML) e consultas de teste (DQL).

## 🔍 Exemplo de Consultas
O projeto inclui queries para:
1. Listar faturamento total por pedido.
2. Identificar os produtos mais vendidos.
3. Filtrar pedidos por status.

---
Desenvolvido por [Victor de Souza](https://github.com/SEU_USUARIO_AQUI) 🚀
