# 🔒FinAPI - Financeira

## Objetivos
Esta é uma API criada para gerênciar o tráfego de dados de uma FinTech, todos os códigos foram desenvolvidos pela [Dani Leão](https://github.com/danileao) nas aulas do ignite, na trilha de Node JS.

Abaixo temos os requisitos de funcionamento da API e todas as suas regras de negócio.

## Requisitos

- [x] Deve ser possivel criar uma conta
- [x] Deve ser possivel buscar o extrato bancário do cliente
- [x] Deve ser possivel realizar um deposito 
- [x] Deve ser possivel realizar um saque
- [x] Deve ser possivel buscar o extrato bancário do cliente por data 
- [x] Deve ser possivel atualizar dados da conta do cliente
- [x] Deve ser possivel obter dados da conta do cliente
- [x] Deve ser possivel deletar uma conta
- [x] Deve ser possivel obter o balance de uma conta


## Regras de negócio 

- [x] Não deve ser possível cadastrar uma conta com CPF já existente
- [x] Não deve ser possível buscar extrato em uma conta não existente 
- [x] Não deve ser possível fazer depósito em uma conta não existente 
- [x] Não deve ser possível fazer saque em uma conta não existente 
- [x] Não deve ser possível fazer saque quando o saldo for insuficiente
- [x] Não deve ser possível excluir uma conta não existente 