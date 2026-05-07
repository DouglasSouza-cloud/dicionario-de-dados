# Projeto de Modelagem de Banco de Dados

## Descrição
Este projeto contém a modelagem inicial de uma tabela de clientes desenvolvida no Excel.

O objetivo é documentar a estrutura de uma tabela de banco de dados, definindo:
- atributos
- tipos de dados
- regras de preenchimento
- chave primária
- chave única
- observações relacionadas à LGPD

---

## Tabela Modelada

### Cliente

| Atributo | Tipo | Descrição |
|---|---|---|
| id | int | Identificador único do cliente |
| nome | varchar(100) | Nome do cliente |
| telefone | varchar(15) | Telefone de contato |

---

## Regras da Tabela

### id
- Chave primária (PK)
- Auto incremento
- Campo obrigatório

### nome
- Campo obrigatório
- Armazena o nome do cliente

### telefone
- Chave única (UK)
- Evita telefones duplicados

---

## Objetivo do Projeto

Praticar:
- modelagem de banco de dados
- documentação de tabelas
- organização de atributos
- padronização de estruturas SQL

---

## Ferramentas Utilizadas
-Mysql
- Excel
- Git
- GitHub

---

## Autor

Douglas de Souza Paixão
