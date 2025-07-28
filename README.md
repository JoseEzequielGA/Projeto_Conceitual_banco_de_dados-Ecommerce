
# 🛒 Modelagem de Banco de Dados para E-commerce

Este projeto foi desenvolvido como parte do curso de **Análise de Dados**, no módulo de **Modelagem de Banco de Dados**.  
A proposta foi criar um banco relacional que represente as principais entidades e relações de um sistema de **loja virtual (e-commerce)**.

---

## 📘 Sobre o Projeto

O objetivo é estruturar as tabelas e relacionamentos necessários para registrar:

- Informações de clientes
- Pedidos realizados
- Produtos vendidos
- Pagamentos
- Fornecedores
- Controle de estoque

O modelo foi construído seguindo os princípios de **normalização** e boas práticas de nomeação e integridade referencial.

---

## 🧩 Entidades do Banco

| Entidade         | Descrição                                                                 |
|------------------|---------------------------------------------------------------------------|
| `Cliente`        | Armazena dados dos clientes (nome, email, CPF/CNPJ, endereço)             |
| `Pedido`         | Registra os pedidos realizados pelos clientes                             |
| `Produto`        | Catálogo de produtos disponíveis na loja                                  |
| `Pagamento`      | Informações sobre o pagamento de cada pedido                              |
| `Forma_pagamento`| Tipos de pagamento aceitos (pix, boleto, cartão, etc.)                    |
| `Pedido_Produto` | Tabela associativa com os itens de cada pedido (quantidade, valor unit.)  |
| `Fornecedor`     | Empresas fornecedoras dos produtos                                         |
| `Produto_Fornecedor` | Relação de quais fornecedores oferecem quais produtos                 |
| `Estoque`        | Locais de armazenagem dos produtos                                        |
| `Fornecedor_Estoque` | Mapeia quais fornecedores entregam em quais estoques                 |

---


## 👨‍💻 Autor

Desenvolvido por **Jose Alves**  
📧 joseezequiel57@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/jose-alves-348122230/)

