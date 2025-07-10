Sistema Bancário Simples em Python
Este projeto implementa um sistema básico de operações bancárias no terminal, onde o usuário pode criar contas, realizar depósitos, saques, visualizar extrato e gerenciar usuários.

Funcionalidades
Criar usuário com CPF, nome, data de nascimento e endereço

Criar conta vinculada a um usuário existente

Depositar valores na conta

Realizar saques com limite e número máximo de saques diários

Exibir extrato com histórico de movimentações e saldo atual

Listar usuários cadastrados

Sair do sistema

Como usar
Execute o script Python:

bash
Copiar
Editar
python nome_do_arquivo.py
No menu, escolha a opção desejada digitando a sigla correspondente:

Opção	Descrição
d	Depositar
s	Sacar
e	Mostrar extrato
nu	Criar novo usuário
cc	Criar nova conta
lu	Listar usuários
q	Sair do sistema

Siga as instruções para cada operação.

Exemplo de uso
yaml
Copiar
Editar
[nu] Criar novo usuário:
Informe o CPF (somente números): 12345678900
Informe o nome completo: João Silva
Informe a data de nascimento (dd-mm-aaaa): 01-01-1990
Informe o endereço (logradouro, número - bairro - cidade/sigla estado): Rua A, 100 - Centro - SP/SP
Usuário criado com sucesso!

[cc] Criar nova conta:
Informe o CPF do usuário: 12345678900
Usuário encontrado, criando conta...
Conta criada com sucesso! Número da conta: 1

[d] Depositar:
Informe o valor do depósito: 500
Depósito realizado com sucesso! Saldo atual: R$ 500.00

[s] Sacar:
Informe o valor do saque: 100
Saque realizado com sucesso! Saldo atual: R$ 400.00

[e] Extrato:
================ EXTRATO ================
Depósito: R$ 500.00
Saque: R$ 100.00

Saldo: R$ 400.00
=========================================
Requisitos
Python 3.x instalado
