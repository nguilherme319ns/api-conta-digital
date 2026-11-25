# API Conta Digital

API REST que simula o núcleo de uma conta digital: cadastro de clientes e contas, depósito, saque e transferência entre contas, com foco em consistência dos dados.

> Projeto de estudo. Todos os dados são fictícios.

## O que o projeto demonstra

- **Valores em centavos (inteiros):** sem erros de arredondamento de ponto flutuante.
- **Transferência atômica:** débito e crédito acontecem na mesma transação SQL; se um falhar, nenhum é aplicado.
- **Idempotência:** cada transferência recebe uma chave única, então repetir a mesma requisição não duplica o valor.
- **Ledger:** toda movimentação gera um registro imutável, e o extrato é paginado.
- **Arquitetura em camadas:** rotas, controllers e services separados.

## Stack

Node.js, Express, MySQL, JWT

## Como rodar

[PREENCHER: passos de instalação, variáveis do .env e comando para criar o banco]

## Endpoints

[PREENCHER: tabela com os endpoints, conforme forem criados]

