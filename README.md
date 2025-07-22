# Projeto ContaBanco

Este é um projeto simples em Java, desenvolvido como desafio para treinar os conceitos de **sintaxe**, **entrada de dados via terminal** e **manipulação de variáveis**.

---

## Objetivo

Criar uma aplicação de terminal que simula a abertura de uma conta bancária. O usuário insere os dados da conta, e o sistema retorna uma mensagem personalizada com as informações fornecidas.

---

## Funcionalidades

- Entrada de dados via terminal com a classe `Scanner`:
  - Número da conta (int)
  - Agência (String)
  - Nome do cliente (String)
  - Saldo (double)
- Impressão de mensagem formatada com os dados inseridos.

---

## Conceitos utilizados

- Estrutura básica de uma aplicação Java (`main`, `Scanner`)
- Declaração de variáveis (`int`, `String`, `double`)
- Entrada de dados via terminal
- Concatenação de strings
- Convenções de nomenclatura em Java
- Boas práticas com `scanner.close()`

---

##  Exemplo de uso

```bash
Por favor, digite o número da conta:
> 1021

Por favor, digite o número da Agência:
> 067-8

Por favor, digite o nome do Cliente:
> MARIO ANDRADE

Por favor, digite o saldo:
> 237.48

Olá MARIO ANDRADE, obrigado por criar uma conta em nosso banco, sua agência é 067-8, conta 1021 e seu saldo 237.48 já está disponível para saque.
