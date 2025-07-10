
# Cálculo de Descontos em Loja

Este projeto implementa um sistema simples para calcular o preço final de um produto com base em cupons de desconto. O desafio foi proposto como parte do Bootcamp Santander/DIO.

## Funcionalidades

- Aplica descontos de 10% (DESCONTO10) e 20% (DESCONTO20).
- Trata cupons inválidos, não aplicando nenhum desconto.

## Como usar

1. Execute o script `desconto.py`.
2. Informe o preço original do produto.
3. Informe o cupom de desconto (ex: DESCONTO10, DESCONTO20, SEM_DESCONTO).

## Exemplo

```
100.00
DESCONTO10
90.00
```



# Sistema Bancário em Python

Este projeto é um desafio do Bootcamp Santander/DIO.

Este projeto implementa um sistema bancário simples em Python, com as seguintes funcionalidades:

- **Depósito**: Permite depositar valores na conta.
- **Saque**: Permite sacar valores da conta, respeitando limites diários e de valor por saque.
- **Extrato**: Exibe o histórico de movimentações da conta.
- **Criação de Usuário**: Permite cadastrar novos usuários com CPF, nome, data de nascimento e endereço.
- **Criação de Conta Corrente**: Permite criar novas contas correntes vinculadas a um usuário existente.
- **Listar Contas**: Lista todas as contas criadas no sistema.

## Como usar

1.  Salve o código como `desafio_v2.py`.
2.  Execute o script Python:
    ```bash
    python3 desafio_v2.py
    ```
3.  Siga as opções do menu para interagir com o sistema.

## Exemplo de uso

```
[d] Depositar
[s] Sacar
[e] Extrato
[nc] Nova conta
[lc] Listar contas
[nu] Novo usuário
[q] Sair
=> nu
Informe o CPF (somente números): 12345678900
Informe o nome completo: João da Silva
Informe a data de nascimento (dd-mm-aaaa): 01-01-1990
Informe o endereço (logradouro, nro - bairro - cidade/sigla estado): Rua A, 123 - Centro - Cidade/SP
=== Usuário criado com sucesso! ===

[d] Depositar
[s] Sacar
[e] Extrato
[nc] Nova conta
[lc] Listar contas
[nu] Novo usuário
[q] Sair
=> nc
Informe o CPF do usuário: 12345678900
=== Conta criada com sucesso! ===

[d] Depositar
[s] Sacar
[e] Extrato
[nc] Nova conta
[lc] Listar contas
[nu] Novo usuário
[q] Sair
=> d
Informe o valor do depósito: 100.00
=== Depósito realizado com sucesso! ===

[d] Depositar
[s] Sacar
[e] Extrato
[nc] Nova conta
[lc] Listar contas
[nu] Novo usuário
[q] Sair
=> s
Informe o valor do saque: 50.00
=== Saque realizado com sucesso! ===

[d] Depositar
[s] Sacar
[e] Extrato
[nc] Nova conta
[lc] Listar contas
[nu] Novo usuário
[q] Sair
=> e
================ EXTRATO ================
Depósito: R$ 100.00
Saque: R$ 50.00

Saldo: R$ 50.00
========================================

[d] Depositar
[s] Sacar
[e] Extrato
[nc] Nova conta
[lc] Listar contas
[nu] Novo usuário
[q] Sair
=> q
=======


